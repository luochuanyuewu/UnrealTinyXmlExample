# UnrealTinyXml Example Project
This is a UE4 plugin "UnrealTinyXml" example project(for ue4.17+).

Please download this project. and put "UnrealTinyXml" plugin into "UnrealTinyXmlExample/Plugins" or download from ue4 marketplace.

This project contain only one map and a actor called "XmlTestActor".

This actor contain many different function to show different functionality of this plugin,try connect to different function node to see different result.

For c++ usage. put "UnrealTinyXml" plugin into "$PROJECTROOT/Plugins", then check XmlCppExampe.h/cpp.(remember add "UnrealTinyXml" module name to project dependency )

# packaging
After packaing your project, make sure you copy you xml files into your packaged build directory.  for example: when you packing this example project(win64 build), you need copy $PROJECTROOT/ExampleXml into WindowsNoEditor/UnrealTinyXmlExample/ExampleXml
