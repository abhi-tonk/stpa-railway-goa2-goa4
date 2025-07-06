# STPA Control Structures for GoA2 and GoA4 (Capella 7.0.0)

![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)

This repository includes STPA-based Hierarchical Safety Control Structures (HSCS) developed using the STPA Viewpoint plugin for Capella 7.0.0. It contains projects for Grade of Automation (GoA) levels 2 and 4.

---

## 📁 Contents

- `GoA2-HSCS.zip`: Capella project with GoA2-level HSCS  
- `GoA4-HSCS.zip`: Capella project with GoA4-level HSCS  
- `images/`: JPEG snapshots of the control structures

---

## 🔧 Requirements

- **Capella Version**: 7.0.0
- **STPA Viewpoint Plugin**: [STPA Viewpoint for Capella](https://github.com/labs4capella/stpa-capella)

---

## ⚠️ Usage Notes

1. Install the **STPA Viewpoint plugin** before opening the projects.
2. Import **only one project at a time** into Capella.
3. **Do not open both GoA2 and GoA4 at the same time**, due to Capella model ID (MMID) conflicts.
4. After importing a project, open:  
   `ST.aird → STPA Analysis → Control Structure → [GOA2-HSCS or GOA4-HSCS]`
5. To switch between GoA2 and GoA4:
   - Close and delete the current project from the Capella workspace.
   - Import the other from a copy stored outside the workspace.
6. 🛑 **Keep backups** of your modified versions in a separate folder not indexed by Capella to prevent accidental corruption or loss.

---

## 🖼️ Diagram Previews

### GoA2 Control Structure

![GoA2 HSCS](images/GoA2-HSCS.jpg)

### GoA4 Control Structure

![GoA4 HSCS](images/GoA4-HSCS.jpg)

---

## 📦 Downloadable Capella Projects

These ZIP files contain full Capella project folders. After extracting, you can import them directly into Capella 7.0.0.

- [`GoA2-HSCS.zip`](GoA2-HSCS.zip) — STPA HSCS model for GoA2  
- [`GoA4-HSCS.zip`](GoA4-HSCS.zip) — STPA HSCS model for GoA4

---

## 🤝 Collaboration

Contributions and collaborations are welcome!

These HSCS models are a starting point — they can be further **refined, detailed, or extended to subsystem levels**. If you're interested in collaborating, feel free to fork the repository, open issues, or submit pull requests.

Whether you're improving the models, adapting them to another domain, or adding detail — your input is valuable.

---

## 📄 License

This repository is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.  
You may use, adapt, and share the content for non-commercial purposes, provided that appropriate credit is given.

For full license details, see the [LICENSE](LICENSE) file or visit [creativecommons.org/licenses/by-nc/4.0](https://creativecommons.org/licenses/by-nc/4.0/).

---

## 📌 Disclaimer

This work was conducted as part of doctoral research at **IRT Railenium** and **Université Gustave Eiffel**, France. The models, methods, and files shared in this repository reflect the outcomes of that ongoing research effort.
