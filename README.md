# Selection to Artboard Plugin
The plugin **creates a custom sized Artboard**, starting from the user selection.

## Prerequisites
[Adobe XD](https://www.adobe.com/products/xd.html)

## Installation
Step by step:
1. Firstly, [download this repository.](https://github.com/AMMarica/AdobeXD_selectionToArtboard/archive/master.zip)
2. Extract the archive and move into the `AdobeXD_selectionToArtboard-master`  folder.
3. Make the plugin package:  run `./package.sh` or zip the folder named `selectionToArtboard` and change the `.zip` extension to `.xdx`
4. Open an XD document, double click the plugin package `selectionToArtboard.xdx` and press `Yes` when prompted to install the plugin.

## Expectations
Running the plugin generates the following result:
* If the selected elements are placed on *Artboard* or just a part of them are situated on *Artboard* and the other part on *Pasteboard*, the elements will be copied on a new created *Artboard*, sized to fit the selection.
* If all the selected elements are located on *Pasteboard*, a new *Artboard* will be created and positioned under the selection.
