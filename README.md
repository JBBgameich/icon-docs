# UBports Icon documentation

This is the repository for the UBports icon documentation.

## Contribution guidelines

You can find ways to contribute [here](https://docs.ubports.com/en/latest/contribute/documentation.html). Please follow all of the guidelines on that page, else your contribution will not be accepted.

## Build instructions

To generate the icon docs you'll need to first initialize submodules: `git submodule update --init`

Next run the script `./generate-suru-icons.py`

Then the documentation can be built by running `./build.sh` in the root of this repository. The script will also create a virtual build environment in `~/ubportsdocsenv` if none is present. After the build is complete, you can view the documentation by opening the html files in your favorite browser (eg. `firefox _build/html/index.html`).
