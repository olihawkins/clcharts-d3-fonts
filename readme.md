# clcharts-d3-fonts

This project builds the font bundle for charts in the clcharts-d3 family. Note that the font files themselves are not included in this repository for licensing reasons. The following web font files should be copied into the directory "src/fonts" in order to build the bundle.

```sh
National-LFSN-Book.woff
National-LFSN-Book.woff2
National-LFSN-Semibold.woff
National-LFSN-Semibold.woff2
Open-Sans-v17-Latin-700.woff
Open-Sans-v17-Latin-700.woff2
Open-Sans-v17-Latin-Regular.woff
Open-Sans-v17-Latin-Regular.woff2
```

## Installation

Clone this repository and install the node modules from package.json.

```bash
npm install
```

## Development

The source files are in `src` and the distribution files are in `dist`.

Check the fonts will be bundled by starting the development server.

```sh
npm start
```

Then build the font bundle.

```sh
npm run build
```