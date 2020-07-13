## Windows Calculator

The Windows Calculator is a modern application written in C++ that ships pre-installed with Windows. The application provides standard, scientific, and programmer calculator functionality, as well as a set of converters between various units of measurement and currencies. You can get the latest version of the application via the [Microsoft Store](https://www.microsoft.com/store/apps/9WZDNCRFHVN5).

## Features

- **Standard calculator** functionality which offers basic operations and evaluates commands immediately as they are entered.
- **Scientific calculator** functionality which offers expanded operations and evaluates commands using the order of operations.
- **Programmer calculator** functionality which offers common mathematical operations for developers including conversion between common bases.
- **Date calculation** functionality which offers the difference between two dates, as well as the ability to add or subtract years, months, and days to and from a given input date.

Additional capabilities include:

- Calculation history and memory capabilities.
- Conversion between many units of measurement.
- Currency conversion based on data retrieved from [Bing](https://www.bing.com).
- Infinite precision for basic arithmetic operations (addition, subtraction, multiplication, division).

## Getting Started

Prerequisites:

- Your computer must be running Windows 10, version 1803 or newer.
- Install the latest version of [Visual Studio](https://developer.microsoft.com/en-us/windows/downloads).
  - Install the latest Windows 10 SDK.
  - Install the "Universal Windows Platform Development" workload.
  - Install the optional "C++ Universal Windows Platform tools" component.
- Install the [XAML Styler](https://marketplace.visualstudio.com/items?itemName=TeamXavalon.XAMLStyler) Visual Studio extension.
- Clone this repository to get the code.
- Open [src\Calculator.sln](/src/Calculator.sln) in Visual Studio to build and run the application.
- For a general description of the project architecture see [ApplicationArchitecture.md](docs/ApplicationArchitecture.md).
- To run the UI Tests, make sure that the [Windows Application Driver (WinAppDriver)](https://github.com/microsoft/WinAppDriver/releases/latest) is installed.

## Contributing

The team encourages community feedback and contributions. Please follow our [contributing guidelines](CONTRIBUTING.md).

## Roadmap

For information regarding future plans and release schedules, please see the [Windows Calculator Roadmap](docs/Roadmap.md).

## Diagnostic Data

This project collects usage data and sends it to Microsoft to help improve our products and services. Diagnostic data is disabled in development builds by default, though it can be enabled with the `SEND_DIAGNOSTICS` build flag. Read our [privacy statement](https://go.microsoft.com/fwlink/?LinkId=521839) to learn more.
