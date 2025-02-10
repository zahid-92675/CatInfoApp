# CatApp

CatApp is a SwiftUI-based iOS application that allows users to explore different cat breeds, view their images, and learn about their characteristics. The app fetches breed information from an API and displays it in a user-friendly interface.

## Features
- **List of Cat Breeds**: Browse through a list of cat breeds with images and basic details.
- **Search Functionality**: Quickly find breeds using a search bar.
- **Breed Details**: Tap on a breed to view detailed information, including temperament, energy levels, and other characteristics.
- **Async Image Loading**: Fetch and display images asynchronously.

## Technologies Used
- SwiftUI
- CoreData (if implemented later)
- URLSession for API calls

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/CatApp.git
   ```
2. Open the project in Xcode:
   ```sh
   cd CatApp
   open CatApp.xcodeproj
   ```
3. Build and run the project in the iOS Simulator.

## API Usage
The app fetches data from a cat breed API. Ensure you have a valid API key (if required) and update `APIService` accordingly.

## Known Issues
- Some images may fail to load due to missing URLs in the API response.
- UI improvements and additional features like favoriting breeds could be added in future updates.



