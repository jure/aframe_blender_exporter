# Changelog

## TODO
- click to show/hide a 3D object
- click to toogle a 3D object
- 

## CHANGELOG

All notable changes to this project will be documented in this file.

- NEW = New Feature
- FIX = Bug Fix

## [0.0.7] work in progress

- [NEW] AFRAME_HTTP_LINK: add a link web text field
- [NEW] AFRAME_SHOW_HIDE_OBJECT: click to show or hide another 3d object
- [NEW] UI refactoring
- [NEW] Added ThreeJS/Aframe Render settings: antialias, colorManagement, physicallyCorrectLights
- [NEW] Integrated Bake Process thanks to [@anfeo](https://github.com/anfeo)

## [0.0.6] - 2020-08-01

- [NEW] index.html template saved inside blend file after the first export, thanks to [@coderofsalvation](https://github.com/coderofsalvation)
- [NEW] UI Layout refactored
- [NEW] Better Panel to use Lightmapper's bake
- [NEW] Add object actions: 
    - Rotation360: rotate on Z axis an object
    - LinkUrl: add a html link when click on object
    - VideoPlay: add a video on plane object (it needs a mp4 file inside "media" directory)
    - Toogle Images
- Use of generic custom property "AFRAME_XXX" to manage custom actions (e.g: AFRAME_FOO-BAR wil be convereted in <a-entity .... foo-bar="{value)">), thanks to [@coderofsalvation](https://github.com/coderofsalvation)
- [NEW] add an intensity value to be applied to generated lightmaps

## [0.0.5] - 2020-07-25

- [NEW] Toogle image handler (click to toogle images)
- [NEW] Lightmapper Blender Add-in integration to bake lightmaps into A-Frame
- [NEW] "AFRAME_ANIMATION" Custom Property. AFrame animation tag examples:
    - "property: rotation; to: 0 360 0; loop: true; dur: 10000;"
    - "property: position; to: 1 8 -10; dur: 2000; easing: linear; loop: true;"
- [NEW] "AFRAME_HTTP_LINK" Custom Property: html link when click on object       
- [NEW] "AFRAME_VIDEO" Custom Property: target=mp4 video to show
- [NEW] "AFRAME_IMAGES" Custom Property: click to swap images, example:
    - {"1": "image1.jpg", "2": "image2.jpg"}

## [0.0.4] - 2020-07-17

- [NEW] Built in HTTP Server for preview, thanks to [@msfeldstein](https://github.com/msfeldstein)

## [0.0.3] - 2020-07-15

- [NEW] Added an option to show or not Environment Sky (env sky or color sky)
- [FIX] Python Code Refactoring, thanks to [@fsoft72](https://github.com/fsoft72)

## [0.0.2] - 2020-07-12

- [FIX] Fix assets path problem

## [0.0.1] - 2020-07-11

- [NEW] Initial commit


