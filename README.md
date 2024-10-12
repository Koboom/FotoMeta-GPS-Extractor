# FotoMeta GPS Extractor

FotoMeta GPS Extractor is a web application that extracts and visualizes EXIF and GPS metadata from photos. Users can upload their photos to view EXIF data (such as camera settings, shooting time, etc.) and GPS coordinates, and see the location where the photo was taken on a map.

## Features
- Extract EXIF and GPS data from JPEG, PNG, and TIFF files
- Display GPS coordinates on Google Maps
- Simple and intuitive user interface
- Fast and responsive photo analysis

## Technologies Used
The following technologies and libraries are used in this project:
- **Vue.js**: Frontend framework for building the user interface
- **Google Maps API**: For visualizing the GPS coordinates on a map
- **exifr.js**: A JavaScript library for extracting EXIF and GPS data from photos
- **W3.CSS**: A CSS framework for responsive design
- **Node.js**: For backend development (if required)
- **GitHub Pages**: For hosting the project

## Requirements
To run the project locally, make sure you have the following installed:
- **Node.js** and **npm**
- A valid **Google Maps API key** (you can get it [here](https://developers.google.com/maps/documentation))

## Getting Started

Follow these steps to set up and run the project on your local machine:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/FotoMeta-GPS-Extractor.git
````

### 2. Navigate to the project directory
```bash
cd FotoMeta-GPS-Extractor
````

### 3. Install dependencies
```bash
npm install
````
### 4. Set up the environment variables
Create a .env file in the root of the project and add your Google Maps API key:
```bash
VITE_GOOGLE_MAPS_API_KEY=your-google-maps-api-key
````
### 5. Run the application
```bash
npm run dev
````
### 6. Open the application
Open your browser and go to http://localhost:3000 to see the application in action.



**Development Guide**

Prerequisites
Before starting development, ensure you have the following tools installed:

Node.js (version 14.x or higher)
npm (Node Package Manager)
A text editor or IDE (such as VSCode)


**File Structure**

Here’s a basic overview of the project structure:
```bash
📂 src
 ┣ 📂 assets           # Static assets (images, icons)
 ┣ 📂 components       # Vue components
 ┣ 📂 views            # Page-level components
 ┣ 📂 styles           # CSS styles
 ┣ 📜 main.js          # Application entry point
 ┗ 📜 App.vue          # Main application component
📂 public              # Public folder (for static assets)
 ┗ 📜 index.html       # Entry HTML file

````

**Explanations:**
Getting Started section includes steps for cloning the repository, installing dependencies, and running the project.
Each command is explained clearly, especially the step for adding the API key in the .env file.
The application setup and development process are explained step-by-step.
This README file, once uploaded to your GitHub page, will clearly inform visitors about the functionality of the project and how to run it.
