THIS IS BROKEN DO NOT USE

# HelpADesk GUI Viewer

A PowerShell-based GUI application to browse and preview documentation files (`.md` and `.txt`) in the HelpADesk repository.

## Description

This script creates a Windows Forms interface with a dropdown menu for selecting documents and a text area for viewing their contents. It scans the current directory for `.md` and `.txt` files and loads the selected file into the viewer.

## Prerequisites

* Windows 10/11 with PowerShell 5.1 or later
* .NET Framework (included with Windows)

## Files

* `HelpADeskGUI.ps1` — PowerShell script that launches the GUI viewer.

## Installation

1. Clone or download the HelpADesk repository:

   ```powershell
   git clone https://github.com/Hendjf/HelpADesk.git
   cd HelpADesk
   ```
2. Ensure `HelpADeskGUI.ps1` is present in the root of the repository.

## Usage

1. Open PowerShell.
2. Navigate to the repository folder:

   ```powershell
   cd C:\path\to\HelpADesk
   ```
3. Run the GUI script:

   ```powershell
   .\HelpADeskGUI.ps1
   ```
4. In the GUI window, select a document from the dropdown and view its contents in the text panel.

## Customization

* **File Types**: To support additional extensions (e.g., `.html`, `.json`), edit the `Get-ChildItem` filter in the script.
* **Window Size**: Adjust the form’s `Size` properties to change the GUI dimensions.
* **Font & Styling**: Modify the font family or size by editing the `New-Object System.Drawing.Font` parameters.

