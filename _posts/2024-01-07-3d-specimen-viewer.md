---
layout: default
title: "3D Specimen Viewer Example"
date: 2024-01-07
---

# TODO for Today

## Parse Morphosource --> CT to Text --> URL check, 2D3D_check --> Take Screenshots --> PASS ARTIFACTS to (Slices to Text) or (Volume to Text) --> Setup Images to Text Release
### Currently finished 2D3D Check and works for 2D slices
### Need to test 3D saving of images
### Build in 2D/3D Passing to OpenAI
### Develop Images to Text Release

# Interactive 3D Specimen Viewer

Below you can find an interactive 3D viewer showing a specimen from MorphoSource. This viewer allows you to examine the specimen from different angles and zoom levels.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe 
    src="https://www.morphosource.org/uv.html#?manifest=/manifests/447772d0-74cb-472b-b443-2426f271a2c3&c=0&m=0&cv=0"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0"
    allowfullscreen>
  </iframe>
</div>

## About This Specimen

This 3D model is hosted on MorphoSource, a repository for 3D data of biological specimens. You can interact with the model directly in this page using the viewer above.

## Using the Viewer

- Click and drag to rotate the specimen
- Use the scroll wheel to zoom in and out
- Double click to focus on a specific point
- Use the toolbar options for additional viewing controls

*Note: If the viewer isn't loading properly, you can also [view it directly on MorphoSource](https://www.morphosource.org/uv.html#?manifest=/manifests/447772d0-74cb-472b-b443-2426f271a2c3&c=0&m=0&cv=0).*
