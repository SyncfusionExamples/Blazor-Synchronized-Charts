
# Blazor-Synchronized-Charts

## Overview

This sample demonstrates synchronized chart interactions using the Syncfusion [Blazor Chart](https://www.syncfusion.com/blazor-components/blazor-charts) component in a .NET 8 Blazor application. The implementation focuses on coordinating user interactions across multiple chart instances so that actions performed on one chart are reflected in related charts. Synchronized charts help users compare datasets more effectively by keeping visual interactions aligned across multiple views of connected information.

## Key Features

- Demonstrates synchronized chart behavior across multiple chart instances.
- Uses Syncfusion Chart interaction APIs to coordinate user actions between charts.
- Supports synchronized tooltip behavior across related charts.
- Supports synchronized crosshair interactions for comparative data analysis.
- Demonstrates synchronized chart navigation and viewing experience.
- Provides a practical implementation pattern for displaying correlated datasets using multiple charts.
- Shows how chart interaction events can be used to update other charts dynamically.
- Built using a Blazor Web App architecture targeting .NET 8.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/SyncfusionExamples/Blazor-Synchronized-Charts.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Blazor-Synchronized-Charts
    ```

3. Restore the project dependencies:

    ```bash
    dotnet restore
    ```

## Running the Application

### Visual Studio

1. Open the solution file (`ChartSample.sln`) in Visual Studio.

2. Set the startup project to the Blazor application project.

3. Press `F5` or click on the "Start Debugging" button to run the application.

### Visual Studio Code

1. Open the project in Visual Studio Code:

    ```bash
    code .
    ```

2. Open a new terminal in Visual Studio Code and run the following command to build and run the application:

    ```bash
    dotnet run
    ```

3. Open your browser and navigate to [https://localhost:5001](https://localhost:5001).

## Project Structure

- `ChartSample/Pages/` — contains the synchronized chart implementation and chart interaction logic.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For synchronized chart documentation, visit https://help.syncfusion.com/chart-sdk/blazor/charts/how-to/synchronized-chart

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.