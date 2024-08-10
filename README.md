# Flutter News App

This project is a **Flutter** application designed using the **Clean Architecture** principles. The app interacts with a News API to fetch and display the latest news articles. Additionally, it utilizes the **Floor** package for managing a local database.

## Features

- **Clean Architecture**: Implemented to ensure a well-structured, maintainable, and scalable codebase.
- **News API Integration**: Fetches the latest news articles from a public API.
- **Local Database**: Stores and retrieves articles using the **Floor** package for offline access.
- **State Management**: Handles application state efficiently across different layers using BLOC.
- **Responsive UI**: A user-friendly and responsive design for a seamless experience on various devices.

## Architecture

The app follows the Clean Architecture principles, with the code organized into the following layers:

- **Presentation**: Contains the UI code, including widgets and state management.
- **Domain**: Encapsulates the business logic, including use cases and entities.
- **Data**: Handles data retrieval, whether from a remote source (News API) or a local database (Floor).
- **Core**: Contains shared utilities, constants, and configurations.
