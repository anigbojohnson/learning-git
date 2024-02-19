Mini Project Instructions

Project Overview:
The project involves creating a runnable JavaScript file that establishes a connection to a MongoDB database and executes user-provided queries in a Domain Specific Language (DSL). The DSL examples, "example1.dsl" and "example2.dsl," are crucial for the project and should be placed in the directory "co7217.miniproject2.parent/co7217.miniproject2/src/main/resources/." The generated JavaScript file can be executed with NodeJS.

Requirements:

Software Dependencies:

Install .groovy and Ecore tools.
DSL examples ("example1.dsl" and "example2.dsl") must be added to "co7217.miniproject2.parent/co7217.miniproject2/src/main/resources/."
NodeJS Installation:

Install NodeJS v16 or above on your local system from https://nodejs.org/en/download/.
Configure NodeJS on your system.
Verify the installation with the command node --version.
MongoDB Setup:

Obtain a MongoDB Atlas account and the connection URI.
Provide the database and collection names for executing queries.
Running the Mini Project:
Follow these steps to run the project successfully:

Generate Xtext Artifacts:

Locate "Dsl.xtext" at "co7217.miniproject2.parent/co7217.miniproject2/src/main/java/miniproject2/Dsl.xtext."
Right-click on the file, choose "Run As," and select "Generate Xtext Artifacts."
Compile DSL Compiler:

Locate "DslCompiler.groovy" at "co7217.miniproject2.parent/co7217.miniproject2/src/main/java/miniproject2/generator/DslCompiler.groovy."
Right-click on the file, choose "Run As," and select "Java Application."
Generate JavaScript Output:

After step 2, the output file is generated at "co7217.miniproject2.parent/co7217.miniproject2/src/main/resources/output.js."
Open a terminal at the location and run the command node output.js.
Executing Different Examples:

By default, the project is set to run "example1.dsl." To switch to "example2.dsl":
Open "DslCompiler.groovy" at line 35.
Replace path1 with path2, save the file, and repeat steps 2 and 3.
Viewing Results:

Observe query outputs in the terminal/console where you run node output.js.
Check MongoDB Atlas for executed queries in the specified database and collection.
