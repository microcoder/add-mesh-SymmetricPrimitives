# Issue

<img src="https://raw.githubusercontent.com/microcoder/SymmetricPrimitives/main/extras/Screenshot_20210424_125914.png" />

The Blender don't allow creating symmetric circle primitives, see for details: https://developer.blender.org/T87779

# Overview

This is an add-on for Blender 3D which creating symmetric circle primitives. You can create circle primitives in object or edit modes call a context menu:

<div align="center">
<img src="https://raw.githubusercontent.com/microcoder/SymmetricPrimitives/main/extras/Screenshot_20210513_213451.png" width="70%" />

<img src="https://raw.githubusercontent.com/microcoder/SymmetricPrimitives/main/extras/Screenshot_20210513_213544.png" width="70%" />
</div>

Also the addon allow do automatic calculation of optimal amount segments for the specified radius to its similarities to original radius when the circle uses with modifier Subdivision Surface. Additionally, threshold maximum tolerance truncation of radius can be to set when calculating auto segmentations.

<img src="https://raw.githubusercontent.com/microcoder/SymmetricPrimitives/main/extras/demo_auto_segments.gif" />

Below shown differents diameters of cylinders but truncation of radius/diameter about the same after apply modifier Subdivision Surface in both cases with set threshold to 0.25 mm in the option for calculation of auto segmentation:

<img src="https://raw.githubusercontent.com/microcoder/SymmetricPrimitives/main/extras/Diagram.png" />

The option **has restrict** maximum to 1000 segments.

# Installation

1. Download last git version of this addon to your computer. Press green button "Code" on top right corner and there select option "Download ZIP" in dropdown menu.

2. Unpack Zip file to your Blender config folder, for example: `../blender/2.93/scripts/addons/SymmetricPrimitives`

3. Run Blender and go to the menu `Edit -> Preferences -> Add-ons` then find in Add Mesh category this add-on and toggle its to enabled.
