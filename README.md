# awesome-vfx
A curated list of awesome vfx tools.

[VFX Reference Platform](http://www.vfxplatform.com/)

DCCs
==========

| Name          | OSS | Free    | Link                                                          |
|---------------|-----|---------|---------------------------------------------------------------|
| Blender       | Yes | Yes     | [Site](https://www.blender.org/)                              |
| Fabric Engine | No  | Depends | [Site](http://fabricengine.com/)                              |
| Houdini       | No  | Depends | [Site](https://www.sidefx.com/)                               |
| Maya          | No  | Depends | [Site](https://www.autodesk.com/education/free-software/maya) |
| Nuke          | No  | Depends | [Site](https://www.foundry.com/products/nuke)                 |
| Modo          | No  | No      | [Site](https://www.foundry.com/products/modo)                 |
| Katana        | No  | No      | [Site](https://www.foundry.com/products/katana)               |
| Mari          | No  | No      | [Site](https://www.foundry.com/products/mari)                 |


2D Paint and Comp
==========
| Name      | OSS  | Free | Link                                                         |
|-----------|------|------|--------------------------------------------------------------|
| Fusion    | No   | Yes  | [Site](https://www.blackmagicdesign.com/ca/products/fusion/) |
| Krita     | Yes  | Yes  | [Site](https://krita.org/en/)                                |
| Mischief  | No   | No   | [Site](https://www.madewithmischief.com/)                    |
| Natron    | GNU  | Yes  | [Site](http://natron.fr/)                                    |
| OpenToonz | BSD3 | Yes  | [Source](https://github.com/opentoonz/opentoonz)             |

Engines
==========
| Name  | OSS | Free | Link                                                                            |
|-------|-----|------|---------------------------------------------------------------------------------|
| GoDot | MIT | Yes  | [Site](https://godotengine.org/) [Source](https://github.com/godotengine/godot) |


Cross App Libraries
==========
| Name             | OSS     | Free | Link                                                                                                                       |
|------------------|---------|------|----------------------------------------------------------------------------------------------------------------------------|
| ACES             | Yes     | Yes  | [Source](https://github.com/ampas/aces-dev/)                                                                               |
| Alembic          | Yes     | Yes  | [Site](http://www.alembic.io/) [Source](https://github.com/alembic/alembic)                                                |
| cross3d          | MIT     | Yes  | [Source](https://github.com/blurstudio/cross3d)                                                                            |
| MaterialX        | Apache2 | Yes  | [Site](http://www.materialx.org/)[Source](https://github.com/materialx/MaterialX/)                                         |
| Open Color IO    | Yes     | Yes  | [Site](http://opencolorio.org/)                                                                                            |
| Open Image IO    | BSD     | Yes  | [Source](https://github.com/OpenImageIO/oiio)                                                                              |
| Open Subdiv      | Apache2 | Yes  | [Site](http://graphics.pixar.com/opensubdiv/docs/intro.html) [Source](https://github.com/PixarAnimationStudios/OpenSubdiv) |
| Open Timeline IO |         | Yes  | [Site](http://opentimelineio.org/)                                                                                         |
| Qt.py            | MIT     | Yes  | [Source](https://github.com/mottosso/Qt.py)                                                                                |
| USD              | Yes     | Yes  | [Source](https://github.com/PixarAnimationStudios/USD)                                                                     |


Blogs
==========
| Author Name                                    | Description                                                         |
|------------------------------------------------|---------------------------------------------------------------------|
| [Cesar Margotta](http://www.cesarsaez.me/)     | Prior Rigger, now Software Dev.                                     |
| [Dhruv Govil](http://dgovil.com/)              | Pipeline Developer, posts a lot about processes and projects.       |
| [Jonathan Cooper](http://www.gameanim.com/)    | Game Animator, posts _a lot_ about animation. Nicely laid out side. |
| [Siew Yi Liang](http://sonictk.com/)           | Cinematic TD, posts a lot about rigging tools and development.      |
| [Ryan Porter](https://yantor3d.wordpress.com/) | Rigger, does a lot of development and rigging work.                 |


Maya
==========

Libraries
----------
| Name                                                    | OSS     | Free | Description                        |
|---------------------------------------------------------|---------|------|------------------------------------|
| [AL_USDMaya](https://github.com/AnimalLogic/AL_USDMaya) | Apache2 | Yes  | Animal Logic's USD Plugin for Maya |


Tools
----------
## Animation
| Name                                                      | OSS   | Free | Description                                                                                                     |
|-----------------------------------------------------------|-------|------|-----------------------------------------------------------------------------------------------------------------|
| [Blue Pencil](http://zurbrigg.com/blue-pencil)            | No    | No   | Sketchpad for Maya                                                                                              |
| [KeyFrame MP](http://zurbrigg.com/keyframe-mp)            | No    | No   | Playblast and Reference Viewer.                                                                                 |
| [KeyFrame Pro](http://zurbrigg.com/keyframe-pro)          | No    | No   | Professional Media playback and review tool.                                                                    |
| [ml_tools](https://github.com/morganloomis/ml_tools)      | CC4   | Yes  | Animation and Rigging tools from Morgan Loomis.                                                                 |
| [pyGhost](https://github.com/coxevan/pyGhost)             | ????? | Yes  | Ghosting for animators.                                                                                         |
| [Tradigitools](https://github.com/kattkieru/tradigiTOOLs) | BSD3  | Yes  | Plugin for Maya (and now Cinema 4D) that promotes a more traditional workflow for animation with digital tools. |




## Modeling
| Name                                                     | OSS | Free | Description                                                                                   |
|----------------------------------------------------------|-----|------|-----------------------------------------------------------------------------------------------|
| [polySymmetry](https://github.com/yantor3d/polySymmetry) | MIT | Yes  | Maya tool for finding the symmetry of a polygon mesh based on the topology.                   |
| [polyReorder](https://github.com/yantor3d/polyReorder)   | MIT | Yes  | Maya plugin with tools to reorder the vertices on a mesh to match the order of another match. |

## Pipeline
| Name                                                             | OSS     | Free | Description                                                                                |
|------------------------------------------------------------------|---------|------|--------------------------------------------------------------------------------------------|
| [animx](https://github.com/Autodesk/animx)                       | Apache2 | Yes  | A project to make it easier for people to use Maya animation in their tools and pipelines. |
| [mayaTaskServer](https://github.com/chrisevans3d/mayaTaskServer) | ?????   | Yes  | A standalone Maya Task Server.                                                             |


## Rigging

| Name                                                                       | OSS    | Free    | Description                                                                                                                                                                              |
|----------------------------------------------------------------------------|--------|---------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Angular Nodes](https://github.com/yantor3d/angularNodes)                  | MIT    | Yes     | Library of Maya nodes to do arithmetic on angles without polluting the scene with unitConversion nodes.                                                                                  |
| [Array Nodes](https://github.com/yantor3d/arrayNodes)                      | MIT    | Yes     | Set of Maya nodes for operating on arrays of values.                                                                                                                                     |
| [boneToMesh](https://github.com/yantor3d/boneToMesh)                       | MIT    | Yes     | Maya plugin for creating proxy geometry for rigs.                                                                                                                                        |
| [cvShapeInverter](https://github.com/chadmv/cvshapeinverter)               | MIT    | Yes     | A script and deformer that can invert a shape through a deformation chain so the shape can be applied as a front of chain shape.                                                         |
| [cvWrap](https://github.com/chadmv/cvwrap)                                 | MIT    | Yes     | A Maya wrap deformer that is faster than Maya's wrap deformer, can be rebounded, has a GPU implementation, and supports inverted front of chain blend shapes.                            |
| [deformerWeightsPlus](https://github.com/chrisevans3d/deformerWeightsPlus) | ?????  | Yes     | Fast Maya skinCluter Save/Load.                                                                                                                                                          |
| [grimIK](https://github.com/kattkieru/grim_IK)                             | GPLv3  | Yes     | Non-iterative two-bone IK plugin with Soft IK, IK / FK switching, reversing, and elbow pinning in one node for Autodesk Maya 2016+.                                                      |
| [maya-capture](https://github.com/abstractfactory/maya-capture)            | MIT    | Yes     | Playblasting in Maya done right.                                                                                                                                                         |
| [maya-capture-gui](https://github.com/Colorbleed/maya-capture-gui)         | MIT    | Yes     | GUI front-end for maya-capture.                                                                                                                                                          |
| [maya-pymetanode](https://github.com/bohdon/maya-pymetanode)               | MIT    | Yes     | A simple solution for storing python objects as data on a node in Maya.                                                                                                                  |
| [maya-pulse](https://github.com/bohdon/maya-pulse)                         | MIT    | Yes     | A rigging framework for Maya.                                                                                                                                                            |
| [maya-quickmenus](https://github.com/bohdon/maya-quickmenus)               | MIT    | Yes     | A set of marking menus all related to workflow efficiency in Maya.                                                                                                                       |
| [maya-quicksearch](https://github.com/bohdon/maya-quicksearch)             | MIT    | Yes     | A popup-style search box for Maya for quickly finding nodes or commands.                                                                                                                 |
| [maya-resetter](https://github.com/bohdon/maya-resetter)                   | MIT    | Yes     | A util for easily resetting transform or other node attributes to their defaults in Maya.                                                                                                |
| [maya-rmbmenuhook](https://github.com/bohdon/maya-rmbmenuhook)             | MIT    | Yes     | A util for hooking into and extending the right mouse button marking menus in Maya.                                                                                                      |
| [mgear](https://gumroad.com/l/mgear)                                       | MIT    | Yes     | Rigging framework for Autodesk Maya.                                                                                                                                                     |
| [ngSkinTools](http://www.ngskintools.com/)                                 | No     | Depends | ngSkinTools is a skinning plugin for Autodesk Maya, introducing new concepts to character skinning such as layers, any-pose-mirroring, enhanced paint brushes, true smoothing, and more. |
| [PySignal](https://github.com/dgovil/PySignal)                             | MIT    | Yes     | A pure Python implementation of the Qt signal system with no QObject dependencies.                                                                                                       |
| [quatExtras](https://github.com/yantor3d/polySymmetry)                     | MIT    | Yes     | Quaternion utility nodes that are missing from Autodesk Maya's quatNodes plugin.                                                                                                         |
| [quicklauncher](https://github.com/csaez/quicklauncher)                    | ?????? | Yes     | A minimal Qt based menu to quickly find and execute Maya commands and user scripts.                                                                                                      |
| [Simplex Solver](https://github.com/blurstudio/Simplex)                    | LGPLv3 | Yes     | The Simplex Solver is cross-package plugin and tool for dealing with complex blendshape combos in for high-end facial rigs.                                                              |
| [Shapes](http://www.braverabbit.com/shapes/)                               | No     | No      | Easy to use blend shape editing tool providing a unified workflow to create and edit blend shape targets and related dependencies for character articulation.                            |
| [skonverter](https://github.com/coxevan/skonverter)                        | ?????  | Yes     | Simple skin converter for Maya.                                                                                                                                                          |
| [skinWrangler](https://github.com/chrisevans3d/skinWrangler)               | Yes    | Yes     | A skinning tool for Autodesk Maya.                                                                                                                                                       |
## Scripting

| Name                                                   | OSS | Free | Description                                                                         |
|--------------------------------------------------------|-----|------|-------------------------------------------------------------------------------------|
| [Charcoal Editor](http://zurbrigg.com/charcoal-editor) | No  | No   | Professional Maya Scripting.                                                        |
| [MayaSublime](https://github.com/justinfx/MayaSublime) | MIT | Yes  | Send selected Python and MEL code snippets from SublimeText to Maya via commandPort |


Tutorials
----------

## Rigging
| Name        | Free | Link                                                                                                                                                                |
|-------------|------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Cult of Rig | Yes  | [YouTube](http://youtube.com/cultofrig) [Twitch](http://twitch.tv/cultofrig) [Site](http://www.cultofrig.com/) [Calendar](http://www.cultofrig.com/streamcalendar/) |

## Scripting
| Name            | Free | Link                                                              |
|-----------------|------|-------------------------------------------------------------------|
| Python for Maya | No   | [Site](http://dgovil.com/blog/2016/11/18/python-for-maya-course/) |


Nuke
================
| Name                                              | OSS | Free | Description                                                                                                         |
|---------------------------------------------------|-----|------|---------------------------------------------------------------------------------------------------------------------|
| [connect](www.cragl.com/connect)                  | No  | Yes  | Manage Cragl tools.                                                                                                 |
| [smartRender](http://www.cragl.com/smartRender)   | No  | No   | Multithreaded background rendering and super fast feedback for NUKE.                                                |
| [smartLook](http://www.cragl.com/smartLook)       | No  | No   | Fast look development inside NUKE, Infinite global toolsets.                                                        |
| [smartMessage](http://www.cragl.com/smartMessage) | No  | No   | Instant messenger for NUKE and MAYA. Communicate with other artists, share data and connect locally and world wide. |
| [smartLib](http://www.cragl.com/smartLib)         | No  | No   | Project and shot management for Nuke.                                                                               |
| [smartShelves](http://www.cragl.com/smartShelves) | No  | No   | Manage your node menus including nodes and gizmos in a clever and simple way.                                       |
| [smartRecents](http://www.cragl.com/smartRecents) | No  | No   | Quickly jump to your recent Nuke projects and keep track of your work                                               |


Fabric Engine
================
| Name                                                             | OSS   | Free | Description                                                                                                                                                                            |
|------------------------------------------------------------------|-------|------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Vray For Fabric](https://github.com/ChaosGroup/vray-for-fabric) | ????? | Yes  | A wrapper of the V-Ray App SDK for Fabric Engine.                                                                                                                                      |
| [Kraken](https://github.com/fabric-engine/Kraken)                | BSD3  | Yes  | Modular character rigging framework built on top of Fabric Engine.                                                                                                                     |
| [SpliceMaya](https://github.com/fabric-engine/SpliceMaya)        | BSD3  | Yes  | Allows you to make use of the Fabric Core inside of Maya and use KL to perform computations inside of Maya using a custom node.                                                        |
| [SpliceModo](https://github.com/fabric-engine/SpliceModo)        | BSD3  | Yes  | Allows you to make use of the Fabric Core inside of Modo and use KL and the Fabric graph to perform computations inside of Modo using a custom Mesh item, a custom Schematic node etc. |


Modo
===============

| Name                                                                   | OSS   | Free | Description                                                       |
|------------------------------------------------------------------------|-------|------|-------------------------------------------------------------------|
| [Modo_Popups](https://github.com/tcrowson/Modo_Popups)                 | ????? | Yes  | A collection of plugins featuring a pop-up search field.          |
| [Modo_ProjectManager](https://github.com/tcrowson/Modo_ProjectManager) | ????? | Yes  | Modo 901. Basic Project Managment Kit.                            |
| [Modo_LightBank](https://github.com/tcrowson/Modo_LightBank)           | MIT   | Yes  | For Modo 801 Linux. Custom Viewport for accessing light channels. |
