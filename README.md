# obs-archipelago-tracker
a custom widget for OBS that uses SAMMI to display archipelago items, perfect for seeing what items you send when the client is going at 1000 miles an hour

# setup guide

## download and install [SAMMI solutions](https://sammi.solutions/), and do the setup required for the program
- this is the brains of the entire widget, and is what handles the visual display of the widget through OBS
- to make things simple for myself, i keep the SAMMI bridge as a custom dock in OBS, so that it runs automatically when OBS and SAMMI are opened

  <img width="151" height="58" alt="image" src="https://github.com/user-attachments/assets/e86b175e-c908-47ca-81a6-3d2361b866f2" />
  
click the "SAMMI Bridge" button to open a context menu

<img width="442" height="293" alt="image" src="https://github.com/user-attachments/assets/d46b5a1a-768b-4f28-8db7-f11a26796447" />

in that menu, click "Copy Full Path" to copy the path to the bridge to your clipboard

<img width="202" height="196" alt="image" src="https://github.com/user-attachments/assets/508e6659-f25a-4877-bfa3-2fbc64873fa1" />

back in OBS, click "Custom Browser Docks" under "Docks"

<img width="781" height="319" alt="image" src="https://github.com/user-attachments/assets/52568305-d0da-4b08-833d-7f4ae818e7d2" />

and add a new dock, the name for the dock will go in an empty space on the left, and the path that you have copied will go into the empty space on the right of the same row

## download and install the latest release of [SAMMIpelago](https://github.com/CaiganMythFang/SAMMIpelago/releases/tag/v0.10.0)
-   this is an extension for SAMMI solutions, and is what handles the communications between the archipelago room and SAMMI

  <img width="456" height="299" alt="image" src="https://github.com/user-attachments/assets/ff0b2896-25a4-446a-9897-511e3fe1b717" />

from the same context menu for the bridge in SAMMI, click "Install an Extension" and navigate to where you saved the release for SAMMIpelago

## download the "archi_tracker.json" and "archi tracker button.json" files, the first file is meant to be imported into obs as a scene collection
-   it is **highly** recommended to download the [source copy](https://obsproject.com/forum/resources/source-copy.1261/) plugin for OBS to make the process of importing this scene into your currently existing scene much simpler
-   the second file is meant to be imported into SAMMI as a new deck, you can do so by copying the text of the file and pasting the deck into SAMMI

  <img width="191" height="211" alt="image" src="https://github.com/user-attachments/assets/29fe8570-46de-4cea-bd82-e2e13112cbea" />

this is where you import the scene collection in OBS

<img width="284" height="200" alt="image" src="https://github.com/user-attachments/assets/1304fad2-b752-408d-a140-aaafa683df74" />

and this is where you import the deck in SAMMI

## the final steps
- once you have your scene in OBS and your deck in SAMMI, all you need to do is connect your slot through the SAMMIpelago extension on the SAMMI bridge, and everything should be handled just fine
