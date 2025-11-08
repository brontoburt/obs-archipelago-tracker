# obs-archipelago-tracker
a custom widget for OBS that uses SAMMI to display archipelago items, perfect for seeing what items you send when the client is going at 1000 miles an hour

# setup guide

- download and install SAMMI solutions, and do the setup required for the program
  this is the brains of the entire widget, and is what handles the visual display of the widget through OBS
  to make things simple for myself, i keep the SAMMI bridge as a custom dock in OBS, so that it runs automatically when OBS and SAMMI are opened

- download and install SAMMIpelago
-   this is an extension for SAMMI solutions, and is what handles the communications

- download the "archi_tracker.json" and "archi tracker button.json" files, the first file is meant to be imported into obs as a scene collection
-   it is **highly** recommended to download the source copy plugin for OBS to make the process of importing this scene into your currently existing scene much simpler
-   the second file is meant to be imported into SAMMI as a new deck, you can do so by copying the text of the file and pasting the deck into SAMMI

- once you have your scene in OBS and your deck in SAMMI, all you need to do is connect your slot through the SAMMIpelago extension on the SAMMI bridge, and everything should be handled just fine
