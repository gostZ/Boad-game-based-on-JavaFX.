# Boad-game-based-on-JavaFX.
## 1. environment
version of IDEA : IntelliJ IDEA 2022.2.4 (Ultimate Edition)
Runtime version: 17.0.5+7-b469.71 aarch64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
JDK version: zulu-17 Azul Zulu version 17.0.5
javafx version : aarch64 - 17.0.2

## 2.image path
To load image in game interface, the paths of images need to be change,
in java file called GameCenter in package "control":
1) in 108 line: change"/Users/zws/IdeaProjects/simon/src/main/resources/image/"+hinder.name+".png"
    to "path of this simon project in your computer + /simon/src/main/resources/image/"+hinder.name+".png"

2) in 149 line: change /Users/zws/IdeaProjects/simon/src/main/resources/image/"+imgname+".png
    to "path of this simon project in your computer + /simon/src/main/resources/image/"+imgname+".png"

3) in 184 line: change /Users/zws/IdeaProjects/simon/src/main/resources/image/"+player.imghead+".png
      to "path of this simon project in your computer + /simon/src/main/resources/image/"+player.imghead+".png"

## 3. junit test
Before running each test, the "module-info.java" need to be deleted or rename this file
