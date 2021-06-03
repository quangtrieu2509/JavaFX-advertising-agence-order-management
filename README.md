# Project: ADVERTISING AGENCE ORDER MANAGEMENT (Vietnamese Ver.)


🔥Versions have been used in project:
- Java version "16.0.1"
- Java(TM) SE Runtime Environment
- Java HotSpot(TM) 64-Bit Server VM
- Java™ SE Development Kit 16.0.1 

🔥Recommended tools for installation:
- IDE: IntelliJ IDEA
	+ Version: IntelliJ IDEA Community Edition 2021.1.1
	+ Publisher: JetBrains (website: www.jetbrains.com)
	+ Download link: https://www.jetbrains.com/idea/download/#section=windows
- GUI: Scene Bulder
	+ Version: JavaFX Scene Builder 2.0
	+ Publisher: ORACLE (website: www.oracle.com)
	+ Download link: https://www.oracle.com/java/technologies/javafxscenebuilder-1x-archive-downloads.html
- JavaFX support library: JavaFX
	+ Version: JavaFX 16 (support until ver.17 released) or JavaFX 11 (long-term support version)
	+ Publisher: Gluon
	+ Download link: https://gluonhq.com/products/javafx/

🔥VM Options setup for program compilation process (just in IntelliJ IDEA):
- Step 1: Select "Run"
- Step 2: Select "Edit configurations…"
- Step 3: Select “Edit configuration templates…” (at bottom left corner)
- Step 4: Select “Application”
- Step 5: Select “Modify options”
- Step 6: Select “Add VM options”
- Step 7: In the part where the prompt text is "VM options", we add the following string:
--module-path <path to the folder "lib" in the downloaded JavaFX SDK folder> --add-modules javafx.controls,javafx.fxml

For example: --module-path G:\openjfx-16_windows-x64_bin-sdk\javafx-sdk-16\lib –add-modules javafx.controls,javafx.fxml
