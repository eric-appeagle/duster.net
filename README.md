# duster.net
Dust.js Compiler Visual Studio Extension
Once this extension is installed to Visual Studio, any dust html template files within the webapp solution will auto-compile their respective .js files.

## Solution
The solution contains 3 projects
1. Duster.Net.DustJSGenerator - the output of this project is the .vsix visual studio extension file
2. Duster.Net.Tests
3. SampleEndUserProject

## Updating the extension
As new versions of Visual Studio come out, the extension will need it's packages and sometimes versions kept up to date.

1. Open Duster.Net.DustJSGenerator.source.extension.vsixmanifest and ensure Install Targets include versions for the latest Visual Studio
2. Update the solution's .NET version
3. Update all NuGet packages
4. Build

## Installation
Upon a successful build, the new .vsix file will be found in \Duster.Net.DustJsGenerator\bin\Debug folder.
Simply share this file and have end-users double click to install

## Usage
Follow instructions found at https://app.tettra.co/teams/informed/pages/frontend-templates-with-dustjs
