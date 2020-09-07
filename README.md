# SVGmonit, turn a system overview in SVG into a live network monitor

The simplest live system overview monitor that runs http checks directly from an in SVG thats for example exported from yEd. Add CHECK-tag to any HTTP/HTTPS endpoint to the SVG and thats it.
Small Node-server updating the SVG with status colors of i.e. a network link between two systems.

![Example](SVGmonit.gif)

## Get started
1. Draw a system overview in [yEd](https://www.yworks.com/products/yed)
2. On one or more elements under "Data" add "Description", CHECK|{NAME}|{URL} ex. CHECK|Example API|http://exemple.com
3. Export to SVG-format
4. Place in svg-img folder
5. Update config.js
5. `npm install`
6. `npm start`