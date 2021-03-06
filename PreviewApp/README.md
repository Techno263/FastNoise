# FastNoise Lite Preview App

This is the FastNoise Lite preview app, it allows you to generate visual representations of the noise generated by the library, exposing every parameter through the GUI.

## Build Instructions

I recommend the use of Visual Studio Code or Visual Studio 2019 for building this project. However I am providing CLI build instructions also for those who prefer the command line.

### Visual Studio Code

In VS Code, you must configure VS Code ready for working with C# ([See Microsoft's own guide](https://code.visualstudio.com/Docs/languages/csharp)). Then you will be able to open this directory in VS Code and simply press F5 to run in debug.

### Visual Studio 2019

Make sure .Net Core 3.1 support is installed for Visual Studio using the Visual Studio installer.

### CLI

- To run the project in debug mode run: `dotnet run`
- To build the project in debug or release mode run: `dotnet build -c Debug/Release`
- To generate an executable run: `dotnet publish -c Debug/Release`