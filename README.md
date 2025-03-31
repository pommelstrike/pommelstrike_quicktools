# 🛠️ pommelstrike quick tools

A lightweight Blender addon designed to simplify and speed up the broken BG3 modkit min/max bounds for objects being dropped on to the world space.
Includes tools for updating mesh data names, calculating and exporting mesh bounds with rotation adjustments, and copying formatted bounds to the clipboard.

> ✅ Compatible with **Blender 3.8**  
> 🔧 Current version: **v2.5.18**  
---

## ✨ Features

### 🔁 Update Mesh Nomenclature
Easily synchronize the mesh data name to match the selected object's name—great for maintaining clean, export-ready naming conventions.

### 📏 Calculate Mesh Bounds
Computes the **Min**, **Max**, **Center**, and **Radius** of selected mesh objects with:
- Automatic **Z-up to Y-up** conversion (for BG3 game engine compatibility)

### 📋 Copy Bounds to Clipboard
Exports the calculated bounds in a structured XML format, for transfering to your mesh.lsx/lsf

Example output:
```xml
<attribute id="BoundsMax" type="fvec3" value="1.23 4.56 7.89" />
<attribute id="BoundsMin" type="fvec3" value="-1.23 -4.56 -7.89" />
<attribute id="Center" type="fvec3" value="0.00 0.00 0.00" />
<attribute id="Radius" type="float" value="7.89" />
```

---

## 🎥 Demo

Here’s a quick look at the addon in action:

![quicktools_min-max](https://github.com/pommelstrike/pommelstrike_quicktools/blob/main/quicktools_min-max.gif?raw=true)

---

## 📦 Installation

1. [Download the addon `pmlstk_quicktools.zip` file](https://github.com/pommelstrike/pommelstrike_quicktools/blob/main/pmlstk_quicktools.zip?raw=true).
2. In Blender, go to **Edit > Preferences > Add-ons**.
3. Click **Install**, select the file, and enable **pommelstrike quick tools**.
4. Access it from the **3D Viewport > Sidebar (N-panel) > pommelstrike** tab.

### 🔍 Finding Your Mesh's `.lsf` Path

To locate your mesh's `.lsf` file in **CrayonBox Resource Manager**:

1. Open **CrayonBox Resource Manager**.
2. Search or browse to your desired mesh asset.
3. **Right-click** the file path field and choose **“Copy Value to Clipboard.”**
4. Paste the path wherever needed—such as for reference, export, or matching bounds data.

> 💡 *This is especially useful for syncing Blender export data with game or engine assets.*

#### 📸 Visual Example

![CrayonBox - Copy LSF Path](https://github.com/pommelstrike/pommelstrike_quicktools/blob/main/mni-max.png?raw=true)

---


## 📄 License

This project is open-source and available under the MIT License.  
Feel free to use, modify, and redistribute.

---

## 🤝 Acknowledgments

**pommelstrike**  
If this tool helps your workflow, consider supporting via [Patreon](https://www.patreon.com/pommelstrike)

---
