# Blender Node Group Collection

Collection of node groups (for shader or geometry nodes)

## List of node groups (Table of Contents)
- [:pushpin: ClampVector (for shader)](#pushpin-clampvector-for-shader)
  - [Implementation](#implementation)
- [:pushpin: ToInstance (for geometry nodes)](#pushpin-toinstance-for-geometry-nodes)
  - [Implementation](#implementation-1)


## Install

- Install [Node Presets](https://extensions.blender.org/add-ons/node-presets/) addon from blender extension.
- Put `xxx.blend` file into your directory of Node Presets.
- You can now add my utility nodes by "Node > Add > Template > XXX".

## Usage

### :pushpin: ClampVector (for shader)

![docs/screenshot_clampvector.png](docs/screenshot_clampvector.png)

Clamps vector by min / max.

#### Implementation

![docs/clampvector/implementation.png](docs/clampvector/implementation.png)

### :pushpin: ToInstance (for geometry nodes)

**DEPRECATED**: use [Geometry to Instance](https://docs.blender.org/manual/en/latest/modeling/geometry_nodes/geometry/geometry_to_instance.html) node instead.

![docs/toinstance/screenshot.png](docs/toinstance/screenshot.png)

![docs/toinstance/example.png](docs/toinstance/example.png)

![docs/toinstance/node.png](docs/toinstance/node.png)

Make geometry into single instance. This is useful when creating instance collection for `Pick Instance` on `Instance On Points`. (For detail, see the movie below.)

https://www.youtube.com/watch?v=nReSOasTuYs

#### Implementation

![docs/toinstance/implementation.png](docs/toinstance/implementation.png)

## License

WTFPL
