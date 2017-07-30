=======
# awesome-vfx
A curated list of awesome vfx tools.

DCCs
==========

|Name         |OSS      |Free    |Link|
|-------      |--       |--------|----|
|Blender      |Yes      |Yes     |[Site](https://www.blender.org/)|
|Fabric Engine|No       |Depends |[Site](http://fabricengine.com/)
|Houdini      |No       |Depends |[Site](https://www.sidefx.com/)|
|Maya         |No       |Depends |[Site](https://www.autodesk.com/education/free-software/maya)|
|Nuke         |No       |Depends |[Site](https://www.foundry.com/products/nuke)
|Modo         |No       |No      |[Site](https://www.foundry.com/products/modo)
|Katana       |No       |No      |[Site](https://www.foundry.com/products/katana)
|Mari         |No       |No      |[Site](https://www.foundry.com/products/mari)


2D Paint and Comp
==========
|Name         |OSS      |Free    |Link|
|-------      |--       |--------|----|
|Fusion       |No       |Yes     |[Site](https://www.blackmagicdesign.com/ca/products/fusion/)
|Krita        |Yes      |Yes     |[Site](https://krita.org/en/)
|Mischief     |No       |No      |[Site](https://www.madewithmischief.com/)
|Natron       |GNU      |Yes     |[Site](http://natron.fr/)
|OpenToonz    |BSD3     |Yes     |[Source](https://github.com/opentoonz/opentoonz)

Engines
==========
|Name         |OSS      |Free    |Link|
|-------      |--       |--------|----|
|GoDot        |MIT      |Yes     |[Site](https://godotengine.org/) [Source](https://github.com/godotengine/godot)


Cross App Libraries
==========
|Name            |OSS |Free    |Link                          
|----------------|----|--------|------------------------------
|Open Image IO   |BSD |Yes     |[Source](https://github.com/OpenImageIO/oiio)|
|Open Color IO   |Yes |Yes     |[Site](http://opencolorio.org/)
|Open Timeline IO|    |Yes     |[Site](http://opentimelineio.org/)
|USD             |Yes |Yes     |[Source](https://github.com/PixarAnimationStudios/USD)
|ACES            |Yes |Yes     |[Source](https://github.com/ampas/aces-dev/)
|Qt.py           |MIT |Yes     |[Source](https://github.com/mottosso/Qt.py)
|cross3d         |MIT |Yes     |[Source](https://github.com/blurstudio/cross3d)


Maya
==========

Tools
----------
## Animation
|Name                                                      |OSS   |Free    |Description
|--------------                                            |----- |--------|----|
|[Tradigitools](https://github.com/kattkieru/tradigiTOOLs) |BSD3  |Yes     |Plugin for Maya (and now Cinema 4D) that promotes a more traditional workflow for animation with digital tools.



## Modeling
|Name                                                      |OSS   |Free    |Description
|--------------                                            |----- |--------|----|
|[polySymmetry](https://github.com/yantor3d/polySymmetry)  |MIT   |Yes     |Maya tool for finding the symmetry of a polygon mesh based on the topology.
|[polyReorder](https://github.com/yantor3d/polyReorder)    |MIT   |Yes     |Maya plugin with tools to reorder the vertices on a mesh to match the order of another match.

## Pipeline
|Name                                                      |OSS    |Free    |Description
|--------------                                            |-----  |--------|----|
|[animx](https://github.com/Autodesk/animx)                |Apache2|Yes     |A project to make it easier for people to use Maya animation in their tools and pipelines.

## Rigging

|Name                                                              |OSS   |Free    |Description
|-----------------------------------------------------             |----- |--------|----|
|[Angular Nodes](https://github.com/yantor3d/angularNodes)         |MIT   |Yes     |Library of Maya nodes to do arithmetic on angles without polluting the scene with unitConversion nodes.
|[Array Nodes](https://github.com/yantor3d/arrayNodes)             |MIT   |Yes     |Set of Maya nodes for operating on arrays of values.
|[boneToMesh](https://github.com/yantor3d/boneToMesh)              |MIT   |Yes     |Maya plugin for creating proxy geometry for rigs.
|[grimIK](https://github.com/kattkieru/grim_IK)                    |GPLv3 |Yes     |Non-iterative two-bone IK plugin with Soft IK, IK / FK switching, reversing, and elbow pinning in one node for Autodesk Maya 2016+.
|[maya-capture](https://github.com/abstractfactory/maya-capture)   |MIT   |Yes     |Playblasting in Maya done right.
|[maya-capture-gui](https://github.com/Colorbleed/maya-capture-gui)|MIT   |Yes     |GUI front-end for maya-capture.
|[maya-pymetanode](https://github.com/bohdon/maya-pymetanode)      |MIT   |Yes     |A simple solution for storing python objects as data on a node in Maya.
|[maya-pulse](https://github.com/bohdon/maya-pulse)                |MIT   |Yes     |A rigging framework for Maya.
|[maya-quickmenus](https://github.com/bohdon/maya-quickmenus)      |MIT   |Yes     |A set of marking menus all related to workflow efficiency in Maya.
|[maya-quicksearch](https://github.com/bohdon/maya-quicksearch)    |MIT   |Yes     |A popup-style search box for Maya for quickly finding nodes or commands.
|[maya-resetter](https://github.com/bohdon/maya-resetter)          |MIT   |Yes     |A util for easily resetting transform or other node attributes to their defaults in Maya.
|[maya-rmbmenuhook](https://github.com/bohdon/maya-rmbmenuhook)    |MIT   |Yes     |A util for hooking into and extending the right mouse button marking menus in Maya.
|[mgear](https://gumroad.com/l/mgear)                              |MIT   |Yes     |Rigging framework for Autodesk Maya.
|[ngSkinTools](http://www.ngskintools.com/)                        |No    |Depends |ngSkinTools is a skinning plugin for Autodesk Maya, introducing new concepts to character skinning such as layers, any-pose-mirroring, enhanced paint brushes, true smoothing, and more.
|[PySignal](https://github.com/dgovil/PySignal)                    |MIT   |Yes     |A pure Python implementation of the Qt signal system with no QObject dependencies.
|[quatExtras](https://github.com/yantor3d/polySymmetry)            |MIT   |Yes     |Quaternion utility nodes that are missing from Autodesk Maya's quatNodes plugin.
|[quicklauncher](https://github.com/csaez/quicklauncher)           |??????|Yes     |A minimal Qt based menu to quickly find and execute Maya commands and user scripts.
|[Simplex Solver](https://github.com/blurstudio/Simplex)           |LGPLv3|Yes     |The Simplex Solver is cross-package plugin and tool for dealing with complex blendshape combos in for high-end facial rigs.
|[Shapes](http://www.braverabbit.com/shapes/)                      |No    |No      |Easy to use blend shape editing tool providing a unified workflow to create and edit blend shape targets and related dependencies for character articulation.


Tutorials
----------

## Rigging
|Name           |Free    |Link
|---------------|--------|----------------------------------------------------------------------------|
|Cult of Rig    |Yes     |[YouTube](http://youtube.com/cultofrig) [Twitch](http://twitch.tv/cultofrig)|

## Scripting
|Name           |Free    |Link
|---------------|--------|----------------------------------------------------------------------------|
|Python for Maya|No      |[Site](http://dgovil.com/blog/2016/11/18/python-for-maya-course/)



Fabric Engine
================
|Name                                                            |OSS  |Free    |Description
|---------------                                                 |-----|--------|----------------------------------------------------------------------------|
|[Vray For Fabric](https://github.com/ChaosGroup/vray-for-fabric)|?????|Yes     |A wrapper of the V-Ray App SDK for Fabric Engine.
|[Kraken](https://github.com/fabric-engine/Kraken)               |BSD3 |Yes     |Modular character rigging framework built on top of Fabric Engine.
|[SpliceMaya](https://github.com/fabric-engine/SpliceMaya)       |BSD3 |Yes     |Allows you to make use of the Fabric Core inside of Maya and use KL to perform computations inside of Maya using a custom node.
|[SpliceModo](https://github.com/fabric-engine/SpliceModo)       |BSD3 |Yes     |Allows you to make use of the Fabric Core inside of Modo and use KL and the Fabric graph to perform computations inside of Modo using a custom Mesh item, a custom Schematic node etc.
