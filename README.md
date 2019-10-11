# strangerpings-diagrams
Component and Sequence Diagrams for StrangerPings EPA ART related features/projects.

*  [EPA ART Diagram Guidance](https://confluence.epnet.com/x/xgO_E)


---
## Directory Structure

* **diagrams** : Folder contains diagrams __exported__ in (.png) format
* **source**
    * mermaid  : source code for Mermaid JS code based diagrams files (using [Mermaid JS](https://mermaidjs.github.io/#/))
    * plantuml : source code for PlantUML code based diagrams files (using [PlantUML](http://plantuml.com))

---
## Tooling

---
### PlantUML

__Installation:__

(Option 1) :  For VisualStudio Code:
1. Install VSCode Extention [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
1. Launch VS Code Quick Open (Ctrl+P)
    1. paste the following command, and press enter
    1. > ext install plantuml

(Option 2) : Using Chocolatey for Windows:
1. Run cmd.exe as Administrator and run two commands as follow:
    1. > @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
    2. > choco install plantuml

__Documentation:__

* PlantUML Documenation/Syntax:  [PlantUML](http://plantuml.com)
* PlantUML VSCode Extention Docs: [PlantUML Extention](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

__Usage:__

* Source files created with (.wsd) file extention
* (ALT + D) in VSCode to build and preview a diagram
---

### Mermaid JS

__Installation:__

1. Install [Node.js and npm](https://www.npmjs.com/get-npm)
1. Install [mermaid](https://www.npmjs.com/package/mermaid)
    1. > npm i mermaid

__Documentation:__

* https://mermaidjs.github.io/#/

