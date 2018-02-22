# Design of Jump the Queue Application


This is the design for the devon application reference called **Jump the Queue**

## Prerequisites

The whole design can be written and edited by using the atom editor with according plugins.
[View Jump the Queue Accelerated Solution Desing on github](https://github.com/devonfw/devon-methodology/blob/ASD_Practices/references/JumpTheQueue/design/JumpTheQueue.adoc "Jump the Queue ASD")
You will need a git client aditionally to commit and push your changes to the specification.

### Installation for Visual Studio Code

To install **Visual Studio Code**, visit [code.visualstudio.com](https://code.visualstudio.com/docs/setup/setup-overview)

For getting the live-previews of the whole documentation as well as the uml-diagram-preview working on Visual Studio, please follow these steps:

1. You need to have AsciiDoctor installed on your computer, for installing it, follow the instructions [here](http://asciidoctor.org/docs/install-toolchain/).
   > If you do not have Rubygem we recommend you to install the version 2.4.3-1. On the Rubygem installer, you **do not need** to install MSYS2 [ruby-lang.org](https://www.ruby-lang.org/en/downloads/)

2. Install the AsciiDoctor plug-in on Visual Studio [marketplace.visualstudio.com](https://marketplace.visualstudio.com/items?itemName=joaompinto.asciidoctor-vscode)
   - Inside Visual Studio press Ctrl + P. That will open the command line.
   - Search "ext install asciidoctor" and install AsciiDoc latest version (February 2018 v.0.3.7)
     > Remember to reload Visual Studio.   

3. To check if it worked, open an AsciiDoc file and activate the extension in one of these three ways:
   - Toggle Preview - ctrl+shift+r
   - Open Preview to the Side - ctrl+k r
   - View symbols - go to symbol action - ctrl+shift+o, select a heading.

4. Install PlantUml **Local Render** to Visual Studio (it is used for previewing UML diagrams) [marketplace.visualstudio.com](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
   - You will first need to install Graphviz. For windows, I would recommend you to install it using
	    Chocolatey with this command `c:\>choco install graphviz`. If you do not have Chocolatey download it from here [chocolatey.org](https://chocolatey.org/install). If you want to install Graphviz manually, then go to [graphviz.org](http://www.graphviz.org/download/)
   - Install PlantUml on Visual Studio by pressing Ctrl + P to open the command line, search for "ext install plantuml" and install the version of "jebbs" (February 2018 v.2.5.2).

5. To check if it worked, open a PlantUml file (normally with extension .pu or .wsd) and press Alt + D.

### Installation for Atom

To install the **atom Text-Editor**, visit [atom.io](https://atom.io/)

With the atom-editor running you will need to install two additional plugins to get the live-previews of the whole documentation as well as the uml-diagram-preview and export functionalities working.

```
Install asciidoc-preview
```

Open atom and go to 'file -> settings -> install' and search for *asciidoc-preview* (by asciidoctor) Submit your search by pressing the *packages* button.
Click *install* to start the installation process. The plugin will be automatically activated after installation.

```
Install plantuml-viewer
```

Open atom and go to 'file -> settings -> install' and search for *plantuml-viewer* (by markushedvall) Submit your search by pressing the *packages* button.
Click *install* to start the installation process. The plugin will be automatically activated after installation.

```
Install language-packages
```

To get basic support for syntax highlighting  in plantuml and asciidoc files, you should additionally install the packages *language-plantuml* (by plafue) and *language-asciidoc* (by asciidoctor).


## Editing the specification

TODO: description of how to write asciidoc, how to write plant-uml diagrams and how to include different parts of the specification as well as the folder structure will be added here.


## Authors

* **Felix Murillo** - *Initial work*
