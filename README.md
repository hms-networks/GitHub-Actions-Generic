# GitHub Actions Repository
Welcome to the GitHub Actions repository for the HMS Networks team. This repository contains generic and template versions for GitHub Actions that may be useful to the HMS Networks team, and any resources that may be required to support their functionality.

## Issues
If you experience or notice an issue with one of the GitHub Actions in this repository, please make an issue under the Issues tab above (location may vary by device).

## Ewon Java Ant Build Action
This GitHub Action performs a compilation of all .java files specified in the source folders variable, `SRC_FOLDERS`.

### Output
When this GitHub action runs successfully, it will produce two artifacts. The first is a .jar file generated using the project's build.xml Ant build script. The second is an archive containing the Javadocs for the generated .jar file.

## Ewon Java Code Google Format Action
This GitHub Action performs a check of the code style for .java files located within a project. It is based on the Google Java format action and will exit with an error code if it locates code that does not comply with the Google Java code format.

### Output
This GitHub Action does not product any artifacts or output. Code files that do not comply to the code style will be listed in the output of the action.

