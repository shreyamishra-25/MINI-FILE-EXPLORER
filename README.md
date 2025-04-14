# 🗂️ Mini File Explorer - C# Windows Forms App

![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)
![WinForms](https://img.shields.io/badge/WinForms-5C2D91?logo=.net&logoColor=white)

# Mini File Explorer

A simple Windows File Explorer application built with C# and WinForms.

![Screenshot 2025-04-13 211448](https://github.com/user-attachments/assets/b6316ab7-4ee8-42f6-9784-a311688b8f55)


## Features

- Browse local drives and directories in a tree view
- View files in selected directories
- Double-click to open files with their default applications
- Refresh button to reload drive information
- Dark-themed UI with light pink background

## Technologies Used

C# – Primary programming language

.NET Framework – Runtime and libraries

Windows Forms (WinForms) – GUI framework

System.IO – For file/directory operations

## How to Use

1. Clone or download the repository
2. Open the solution in Visual Studio
3. Build and run the project
4. Use the interface to:
   - Navigate drives and folders in the left panel
   - View files in the right panel
   - Double-click files to open them
   - Click "Refresh" to reload drive information

## Code Structure

- `Form1.cs`: Main form containing all the logic
  - `LoadDrives()`: Loads all available drives
  - `LoadDirectories()`: Loads directories for a given node
  - `LoadFiles()`: Loads files for a selected directory
- `Form1.Designer.cs`: Auto-generated designer file with UI components

## Customization

The application features customizable UI elements:
- Light pink background
- Black panels with white text
- Green refresh button

You can easily modify colors in the `InitializeComponent()` method.

## Limitations

- No error handling for restricted folders
- Basic functionality without advanced features like copy/paste
- No thumbnail or icon view options

## Future Improvements

- Add file operations (copy, move, delete)
- Implement search functionality
- Add multiple view modes (icons, details)
- Improve error handling

## License

This project is open source and available under the [MIT License](LICENSE).


DEVELOPED BY- SHREYA MISHRA
