# How to Group and Filter Items in the Syncfusion Blazor DropDownList

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Dropdown List](https://www.syncfusion.com/blazor-components/blazor-dropdown-list) component to organize items through grouping and improve selection efficiency through filtering. Grouping allows related records to be displayed under category headers, making large datasets easier to browse and understand. Filtering enables users to quickly search and narrow down available options, reducing the effort required to locate specific items. Together, these features provide an improved selection experience for data-driven applications.

## Key Features

- Demonstrates the `SfDropDownList` component for item selection.
- Uses `DropDownListFieldSettings.GroupBy` to categorize and display related items under group headers.
- Enables filtering to allow users to search and refine results within the dropdown list.
- Binds structured data collections to the DropDownList component.
- Displays categorized records and filtered search results within the same control.
- Shows how grouping and filtering can be combined to improve usability when working with larger datasets.
- Demonstrates field mapping configuration through DropDownList field settings.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GroupAndFilterItems.sln` solution file.
3. Restore all NuGet packages.
4. Build the solution.
5. If required, set the Server project as the startup project.
6. Press `Ctrl+F5` to run the application without debugging.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root directory.
4. Restore dependencies and run the project:

```bash
dotnet restore
dotnet run
```

5. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

`GroupAndFilterItems.sln` - Solution file that contains the Blazor sample projects.

`Client/Pages/Index.razor` - Implements the Syncfusion Blazor DropDownList grouping and filtering functionality.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for grouping in the Blazor DropDownList: https://blazor.syncfusion.com/documentation/dropdown-list/grouping

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.