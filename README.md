# **SUPERLOADER v2 for PES 2017**
### *by Famous Dogg Studios*

Please read these instructions carefully before use.

---

## 🧐 **What is Superloader and why should you use it?**

**Superloader v2** is the enhanced successor to the older Superloader modules.  
It now includes a **full graphical interface** that lets you change highly impactful graphical and gameplay-adjacent settings in PES 2017 with a click.

Superloader helps you achieve:

- **The most realistic pitches (turfs)**  
- **Improved lighting and shader effects**  
- Consistent visuals across *all* sider stadiums  
- Fixes for immersion-breaking stadium lighting  
- Real-time adjustments to pitch & lighting  
- Easy UI-driven configuration  

It also includes QoL features such as:

- Adjusting **roof shadow darkness**  
- Changing **referee kit colours**  
- Enhancing **ball visibility**  
- Improving **goal net physics**  
- Enabling/disabling **derby logic**  
- Fixing the **Real Eyes bug**  
- Improved **kit stain textures**

A major v2 update also introduced **real-time 3D rain effects** in PES 2017—a first for ANY PES/eFootball game.

---

## 🚫 **What Superloader is NOT**

- Superloader features **only work with sider stadiums**, *not* CPK stadiums.  
- You MUST use the included **custom StadiumServer.lua**.  
- Superloader aims for **realism**, not fantasy graphics.

If you want ultra-bright neon turfs or uniform lighting everywhere, this tool is *not* designed for that.

Superloader focuses on:

- Precision pitch rendering  
- Proper shadow maps  
- Correct floodlighting  
- Realistic broadcast-style visuals  

---

## ⚙️ **Setup Instructions**

Follow these steps carefully.

---

### **1. Copy Modules**

Go to:

```
Sider/modules
```

Copy:

```
StadiumServer.lua
superLoader.lua
```

---

### **2. Copy Content**

Go to:

```
Sider/content
```

Copy the entire folder:

```
superLoader
```

into your PES 2017 Sider/content directory.

---

### **3. Update sider.ini**

Add these lines:

```
lua.module = "superLoader.lua"
lua.module = "StadiumServer.lua"
```

This order is important.

---

### **4. Launch the Superloader Tool**

Navigate to:

```
Sider/content/superLoader/SuperLoader Tool
```

Run:

```
SuperLoader Tool.exe
```

You can also make a desktop shortcut.

---

### **5. Using the Tool**

- First launch uses **recommended default settings**.  
- Explore presets and experiment.  
- Some changes apply immediately; others require a restart (the app will inform you).  
- Logging is **off by default** for performance.  
- Turn logging on only for debugging or error reporting.

---

### **6. Stadium Folder Structure**

If using Superloader’s StadiumServer:

Your stadiums **must** be stored in:

```
Sider/content/stadium-server
```

---

## 📌 **Additional Information**

- Do **not** rename or modify included files.  
- Misnaming will break the tool or cause texture corruption.  
- Advanced modding instructions from earlier versions are no longer supported.

Original EvoWeb thread for reference:  
https://evoweb.uk/threads/big-new-update-superloader-get-consistently-good-pitches-fifa-identical-lighting-enhanced-ball-reflections-and-much-more-throughout-the-game.96641/

---

## ⚠️ **Permissions**

Superloader is free to share **as long as you give proper credit**.

```
SuperLoader for PES 2017 by Famous Dogg
Reach me @famous_dogg on X
Do not reupload or use in your mods without giving credit.
```
