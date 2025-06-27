# STPA Control Structures for GoA2 and GoA4 (Capella 7.0.0)

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
ST.aird → STPA Analysis → Control Structure → [GOA2-HSCS or GOA4-HSCS]

5. To switch between GoA2 and GoA4:
- Close and delete the current project from the Capella workspace.
- Import the other from a copy stored outside the workspace.

6. 🛑 **Keep backups** of your modified versions in a separate folder not indexed by Capella to prevent accidental corruption or loss.

---

## 🖼️ Diagram Previews

### GoA2 Control Structure

![GoA2 HSCS](images/GOA2-HSCS.jpg)

### GoA4 Control Structure

![GoA4 HSCS](images/GOA4-HSCS.jpg)

---

## 🤝 Collaboration

Contributions and collaborations are welcome!

These HSCS models are a starting point — they can be further **refined, detailed, or extended to subsystem levels**. If you're interested in collaborating, feel free to fork the repository, open issues, or submit pull requests.

Whether you're improving the models, adapting them to another domain, or adding detail — your input is valuable.

---

## 📄 License

This work is shared under an open-access approach for academic and research purposes. Attribution appreciated but not required.
