# Contributing to DubbyGen

Thank you for contributing to DubbyGen! To keep the repository organised and ensure efficient collaboration, please follow these guidelines.

## Naming Conventions
- **File Names**: Prefix your project folder and files with your initials (e.g., `rk.filename.maxpat` for Rasmus Kjærbo) to indicate ownership.
- **Descriptive Names**: After your initials, use a brief description of the file’s purpose (e.g., `rk.harmonicechofilter` for a project folder, `rk.delay_module.gendsp` for a specific file).

## Project Structure
- **Folder Organization**: All projects should be added to the `DubbyGen/projects` folder. Each project should have its subfolder named with your initials followed by the project name (e.g., `rk.harmonicechofilter` for projects added by Rasmus Kjærbo). [Link to projects folder](projects/)
  - Inside each project folder, include Gen DSP files, Max patches, and any other resources for that specific project.
- **Project Documentation**: For larger projects, add a `README.md` file in your project folder with a brief description, usage instructions, and any dependencies.

## Commit Standards
- **Commit Message Format**: `[Component] Description` (e.g., `[DSP] Added rk.delay_module.gendsp for testing`).
- **Single Purpose**: Keep commits focused on one change or addition whenever possible.

## Commenting and Documentation
- **Annotations in Patches**: Comment within patches to clarify complex functions or unique settings, especially within Gen~ files.
- **Version Information**: Add a comment header in each file with version info, a brief description, and your initials (e.g., `// rk - Version 1.0 - Basic delay effect for Dubby`).

## Testing and Validation
- **Basic Testing**: Test for functionality and compatibility before committing.
- **Document Known Issues**: Note any limitations or known issues in comments within the code.

## Pull Requests
- **Titles and Descriptions**: Use clear titles and describe the changes, dependencies, and testing notes.
- **Tag Relevant Contributors**: Tag the owners of files you are modifying or expanding upon.

---

By following these guidelines, we can maintain an organised and effective development environment for everyone. Thank you for helping make DubbyGen a collaborative and high-quality project!
