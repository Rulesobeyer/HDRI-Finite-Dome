# OSL HDRI Dome Projection Shader

A lightweight OSL shader for mapping equirectangular HDRI textures onto a finite half dome using ground projection.  
Tested with Blender + Octane, but should work with any OSL-compatible renderer.

## Features

- Ground projection for realistic environment mapping.
- Adjustable rotation, height, tilt, and ground radius.

## Instructions

1. In your renderer, add an **RGB Image** node.
2. Connect the RGB Image node to an **OSL Projection** node.
3. Load this `.osl` file into the OSL Projection node.
4. Compile the shader.

## Compatibility

Tested with Blender + Octane; should work with other OSL renderers.

