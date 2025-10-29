# omonix
Omonix Pie Menu : The Context-Aware Workflow Accelerator
📜 Our Story: From a Simple Need to a Multi-Functional Tool
The journey of Omonix started from a single, simple frustration: the tedious process of accurately setting an object's origin point in Blender. As a daily user, I realized that constantly accessing sub-menus to move the origin to the top, bottom, or center of an object was a massive workflow bottleneck. I just wanted a quick, accessible grid of options right under my mouse!

This simple desire was the spark that ignited this project, giving birth to OMONIX, which stands for Origin Mover.

Initially, it was just that—a powerful, one-stop shop for origin manipulation. However, as my own projects evolved, so did the addon. I began integrating other critical functions to streamline my personal workflow, from smart snapping and duplication to essential Edit Mode operations. This little tool, born from a need for better origin control, has blossomed into a comprehensive, multi-functional accelerator designed to keep my (and now your) hands off the tedious menus and on the work.

💖 Thank You & Seamless External Addon Integration
I sincerely thank the creators of these exceptional addons. Their tools are so powerful that I chose to build them into the core of the Omonix workflow:

QRemeshify by ksami (GitHub: https://github.com/ksami/QRemeshify): One-click Quad Remeshing directly from the Quick Tools panel.

EdgeFlow by BenjaminSauder (GitHub: https://github.com/BenjaminSauder/EdgeFlow): Instantly calls the Edge Flow utility for clean topology in Edit Mode.

MatColeX by budijozz (Blender Extensions: https://extensions.blender.org/add-ons/matcolex/): Direct access to the MatColeX panel for quick material application.

Place Helper by ACGGIT_LJ (Blender Extensions: https://extensions.blender.org/add-ons/placehelper/): Utilized by Smart Duplicate and Snap/Move to Pointer to provide the best interactive placement experience.

Omonix automatically checks for these addons and enables the relevant button in the pie menu only if the tool is installed, ensuring a clean and powerful workflow.

✨ Key Features & Highlights (Available via Alt + RMB by Default)
Omonix has grown to cover almost every essential, repetitive task in both Object and Edit Modes.

1. 🎯 Advanced Origin Manipulation (OMONIX: Origin Mover)
Complete Control: Instantly move the object's origin to any of the 6 Bounding Box sides (Top, Bottom, Left, Right, Front, Back), the Center, or the 3D Cursor with a single click in a clean, visual grid.

2. ⚡ Smart Transform & Placement
Smart Duplicate / Separate: Duplicates the selected object (Object Mode) or separates selected elements (Edit Mode), and instantly moves the new geometry to the exact 3D location under the mouse pointer to begin an interactive placement session.

Includes optional Solidify Modifier call for Edit Mode separation.

Snap / Move to Pointer: Instantly snaps the active object to the 3D location under the mouse and initiates an interactive move session.

Context-Aware Primitive Creation: Adds a new primitive (Cube, Sphere, Curve, etc.) at the mouse-pointer's ray-cast location.

Smart Lattice: When adding a Lattice, if objects are selected, the Lattice is automatically created around the selection's bounding box and scaled to fit perfectly.

3. 🛠️ Essential Object Tools
Mirror Tools: Access both non-destructive Mirror Modifier (with Clipping options) and destructive Object Axis Mirror transforms from a single pop-up menu.

Link & Transfer Tools: Quickly copy Modifiers, Materials, or Object Data. Access a dedicated sub-menu to transfer specific mesh data like Vertex Groups, UV Maps, Vertex Colors, and Shape Keys.

Apply Tools: One-click application for All Transforms (Location, Rotation, Scale), Visual Geometry to Mesh, and Make Instances Real.

4. 🧠 Context-Aware Edit Mode
The pie menu intelligently changes to present the most relevant tools based on the active selection mode (Vertex, Edge, or Face) in Mesh Edit Mode.

Vertex Mode: Offers Bevel Verts, Connect Path, and Merge By Distance.

Edge Mode: Offers Bevel Edges, Edge Crease, and Bridge Loops.

Face Mode: Offers Poke Face, Triangulate, and Tri to Quads.

Shaping Tools: Quick access to Relax Verts and Smarty Edge Flow.

Selection Tools: Access a sub-menu to Select Linked by Material, Seam, Sharp, or UVs.

UV Tools: Quick access to Smart UV Project and Project From View.

🚀 Final Note
Thank you for downloading and integrating Omonix into your daily Blender workflow. I hope this small addon, born from a simple need, proves to be a powerful companion in your 3D creations.

Your usage, feedback, and suggestions for future feature development are always highly appreciated!
