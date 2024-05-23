
# NASA BlueMarble Shaded Relief Bathymetry Tiles

This NPM package provides access to tiles from the NASA BlueMarble_ShadedRelief_Bathymetry dataset. These tiles feature detailed representations of Earth's surface combining shaded relief and bathymetry (underwater topography).

![Planet](planet.jpeg)

## Usage

The tiles can be used offline, hosted on your own servers, or accessed via the included CDN link for easy integration into web mapping applications. 
![npm](https://img.shields.io/npm/v/@freetiler/nasa-bluemarble)

To install the tiles offline via [NPM](https://www.npmjs.com/package/@freetiler/nasa-bluemarble), use:
```
npm install @freetiler/nasa-bluemarble
```

### CDN Links

You can use any NPM or Github CDN to serve the tiles. 

```
GitHub CDNs - Zoom 0-8: 
 - https://cdn.jsdelivr.net/gh/freetiler/nasa-bluemarble/tiles/{z}/{x}/{y}.jpeg
 - https://cdn.statically.io/gh/freetiler/nasa-bluemarble/main/tiles/{z}/{x}/{y}.jpeg
```

## Tile Specs:

- **Minimum Zoom Level**: 0
- **Maximum Zoom Level on NPM**: 7
- **Maximum Zoom Level on Github**: 8
- **Projection Used**: EPSG:3857
- **Tile Size**: 256x256
- **Tile Format**: JPEG
- **Attribution**: "FreeTiler.com | NASA Earth Observatory"

## License

NASA Open Data Policy:
NASA has an open data policy, and you are free to use the imagery from GIBS as you see fit.  Citations are not required but are requested and highly appreciated.  Please see the “Data Use Policy and Acknowledgements” section here for more information:
https://www.earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs

## Disclaimer

This package is provided "as is", without warranty of any kind. Use at your own risk.
