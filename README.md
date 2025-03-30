# 🛠️ pommelstrike quick tools

A lightweight Blender addon designed to simplify and speed up common mesh management tasks for 3D workflows. Includes tools for updating mesh data names, calculating and exporting mesh bounds with rotation adjustments, and copying formatted bounds to the clipboard.

> ✅ Compatible with **Blender 3.8**  
> 🔧 Current version: **v2.5.18**  
> 📦 Category: `Object`

---

## ✨ Features

### 🔁 Update Mesh Nomenclature
Easily synchronize the mesh data name to match the selected object's name—great for maintaining clean, export-ready naming conventions.

### 📏 Calculate Mesh Bounds
Computes the **Min**, **Max**, **Center**, and **Radius** of selected mesh objects with:
- Automatic **Z-up to Y-up** conversion (for game engine compatibility)
- Optional **X-axis offset** of `0.14` units for positional fine-tuning

### 📋 Copy Bounds to Clipboard
Exports the calculated bounds in a structured XML-like format, perfect for use in external tools or pipelines.

Example output:
```xml
<attribute id="BoundsMax" type="fvec3" value="1.23 4.56 7.89" />
<attribute id="BoundsMin" type="fvec3" value="-1.23 -4.56 -7.89" />
<attribute id="Center" type="fvec3" value="0.00 0.00 0.00" />
<attribute id="Radius" type="float" value="7.89" />
