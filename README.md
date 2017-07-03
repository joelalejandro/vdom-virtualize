# vdom-virtualize

This fork of `vdom-virtualize` wraps the original library around a Browserify build task in order to bundle it more easily on SPAs.

[![Sauce Test Status](https://saucelabs.com/browser-matrix/vdom-virtualize.svg)](https://saucelabs.com/u/vdom-virtualize)

**New in v2.0:** removed support for virtualize.fromHTML -- doing this right and supporting all platforms is a job for [another library](https://github.com/TimBeyer/html-to-vdom).

**New in v1.0:** vdom-virtualize now supports comments and does now use peerDependencies to depend on virtual-dom.

## API

### virtualize(node:DOMNode)
 * node `{DOMNode}`

 * returns `{VNode}`: A virtual-dom tree

### virtualize.fromHTML(html:String)
 * html `{String}`

 * returns `{VNode}`: A virtual-dom tree

Turn a DOMNode into a [virtual-dom](https://github.com/Matt-Esch/virtual-dom) node.
