# mapit

These are the utilities for turning a set of PDFs into tiled images for use with Bureau Gravity's "mapit" application.

## Usage

### PDFtoJPG

`cd bin`

`./pdftojpg <file>`, where `<file>` is the name of a pdf in the `src/pdfs` folder, but without the `.pdf` extension. For example, if you have a pdf file at `src/pdfs/floor1.pdf`, you can convert it by calling `./pdftojpg floor1` in the `bin` directory.

The output of the conversion will be in the `out` folder.

### TileIt

`cd bin`

`./tileit <file>`, where `<file>` is the name of a jpeg file in the out folder, without the extension. For example, if you have a jpeg file at `out/floor1.jpg`, you can tile it by calling `./tileit floor1` in the `bin` directory.

The output will in a new directory with the same name as `<file>`, which will be stored in the `tiles` folder. Each tile will have the prefix `map_tile`.
