# Just PlantUML Things

### Getting to grips with PlantUML

Nothing but diagrams that mean nothing.

1. [Sequence Diagrams](https://github.com/zan-clifton-jisc/just-plantuml-things/tree/main/sequence-diagrams)
2. [System Context Diagrams](https://github.com/zan-clifton-jisc/just-plantuml-things/tree/main/system-context)

## Creating a Local Copy and Using This Repo Online

### ✔️ 1. USE THE PLANTUML WEB SERVER

You can create a local copy of this repo if you like, but please be aware that getting to the point where it runs locally is an investment in time and effort that doesn't really pay off, as you can preview any diagram online in the [PlantUML Webserver](http://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000). Nevertheless, if you're stubborn like me, please feel free to give the following a go:

### ✔️ 2. CLONE THE REPO

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

Terminal Commands:

```
$ git clone https://github.com/zan-clifton-jisc/just-plantuml-things.git
$ cd just-plantuml-things
$ code .
```

### ✔️ 3. SET UP ENVIRONMENT

<img src="https://user-images.githubusercontent.com/108344587/183610549-f29ff7ef-f587-40da-af1d-0d98f11c40be.png" width=400px align=right alt="PlantUML Extension"/>

[![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/download)
![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)

You will need to have the following installed:

[VS Code](https://code.visualstudio.com/download) 
[PlantUML VS Code Extension](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)
[Graphviz](http://www.graphviz.org/download/)
[Java](https://www.java.com/en/download/)

Quick install Java and Graphviz for Mac:
```
$ brew install --cask temurin
$ brew install graphviz
```

Quick install for Windows:

You should be good out of the box. If not, or you want to customise which versions you are using, there are instructions included on the extension's page.

Otherwise, you can quick install PlantUML and its dependencies with chocolatey:
```
$ choco install plantuml
```

### ✔️ 4. USAGE

Open the file in VS Code. Right clicking anywhere inside the document will open a menu. Select `Preview Current Diagram`.

![Screenshot 2022-08-09 at 12 23 57](https://user-images.githubusercontent.com/108344587/183635943-9d146352-be55-43d4-a5bb-67dddbc4fb5d.png)

This will open a preview on the right hand side of the screen where you can see the diagram.

