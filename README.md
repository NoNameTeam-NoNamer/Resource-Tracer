# Resource Tracer

![Mod Version](https://img.shields.io/badge/version-0.0.1-blue) ![Minecraft](https://img.shields.io/badge/Minecraft-26.3+-green) ![Fabric Loader](https://img.shields.io/badge/Fabric_Loader-0.20.1+-yellowgreen) ![Side](https://img.shields.io/badge/Client-side-00bbee) 

**Resource Tracer** is a lightweight client-side Fabric mod that illustrates the paths of resources you see in the game. It displays the resource path in your chat.

> **Note:** This mod is **client-side only**. It does nothing when installed on a dedicated server.

---

## ✨ Features

-   🧱 **Block tracing** – `/rt block <x> <y> <z>` resolves the block state at the given position and outputs the exact blockstate, model, and texture files it uses.
-   📋 **Clickable paths** – Each path comes with `[copy]` and, when the file lives on disk, `[jump to]` buttons.

---

## 📥 Installation

1.  **Install Fabric Loader** for Minecraft.
2.  **Download the mod JAR** from the [Releases](https://github.com/NoNameTeam-NoNamer/Resource-Tracer/releases) page.
3.  Place the JAR in your `mods` folder.
4.  Launch the game and enjoy!

Requires [Fabric API](https://modrinth.com/mod/fabric-api).

---

## 🛠️ Building from Source

If you want to compile the mod yourself:

```bash
git clone https://github.com/NoNameTeam-NoNamer/Resource-Tracer.git
cd Resource-Tracer
./gradlew build
```

The built JAR will be placed in `build/libs/`.

---

## 📋 Compatibility

| Minecraft       | Status |
|:----------------|:----------------------------------------------------------------------------|
| 26.4 SNAPSHOTS  | ❔ Maybe work  |
| 26.3            | ✅ Fully tested|
| 26.1-26.2| ⚠️ Not tested|
| Below 26.1| ❌ Not Supported |

If you encounter any incompatibility in the tested versions above, please report it via the [issue tracker](https://github.com/NoNameTeam-NoNamer/Resource-Tracer/issues).

---

## ❓ FAQ

**Q: Why can't I jump to the source file?**  
A: If the resource is inside a .jar or .zip file, the "jump to" button is unavailable.

---

## ✒️ Developing

-   Item Tracing.
-   Entity Tracing.

---

## 📝 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 💬 Contact

-   **Author**: No Namer and Another No Namer
-   **Issues**: Please use the [GitHub issue tracker](https://github.com/NoNameTeam-NoNamer/Resource-Tracer/issues) for bug reports and feature requests.