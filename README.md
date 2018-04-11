## SketchStrap

![SketchStrap](https://sketchstrap.io/assets/images/facebooklogo.png)

Sketch file with a full package of Bootstrap components. We have __21 artboards__, __340 components__, and more. Learn about rest of features on [sketchstrap.io](https://sketchstrap.io).

### Overview

SketchStrap component kit has been prepared to get along with plugins that complementing SketchStrap bundle. Please, remember that some part of sketch file (like naming schema, element hierarchy and construction methods) are dictated by compatibility.

### SketchStrap.sketchplugin
In this repo we are sharing part of our Sketch plugin that is required to work with SketchStrap UI kit. To get the full experience of SketchStrap check our subscription plans on [sketchstrap.io](https://sketchstrap.io).

### Tech spec
#### Why not symbols?
Symbols are great, but we want to as soon as possible - in project life cycle - take the adventage and be in sync with Bootstrap Stylesheets. We created plugins that allow to share just property values - as CSS does. So please, use our magic __naming system__.
#### Naming system
To be able to share properties like fill, text color, border radius and color we invented few rules of notation.
- Groups or elements not in sync should be named like HTML elements with `>` prefix - e.g. `p.card-text`
- Synced elements name should be prefixed with `_` char and suffixed with all properties we want to apply in round brackets, e.g.
```
_btn(fill:$primary; border-radius:$border-radius;)
```
- We can use properties like: __fill__, __border-radius__, __border-color__.
- Values should be prefixed with `$` char and contain name of variable from "Control Panel" page.

#### Hierarchy of elements
We build groups as containers to imitate actual Bootstrap hierarchy.

### Copyright and license
Copyright 2018 Jazzy Innovations. Resources released under the MIT license. There is only one limitation you can't re-distribute the SketchStrap as stock. You can’t do this if you modify the SketchStrap.

---
*Made with love by [Jazzy Innovations](https://jazzy.pro)*
