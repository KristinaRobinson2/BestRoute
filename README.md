BestRoute


<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


 ## About the Project


BestRoute is a desktop application that helps users optimize multi-stop routes, 
visualize them on a map and generate turn by turn directions. A useful app for
planning errands, assigning routes to a team or managing deliveries. BestRoute
provides an easy to use interface for efficient route planning.

Key features include:
<ul>
  <li>Manual address entry and file import</li>
  <li>Route optimization via Google APIs or Mapbox</li>
  <li>Visual map display with waypoints and paths</li>
  <li>Turn by turn directions</li>
  <li>Local save/load of routes with SQLite</li>
  <li>(Optional) OCR-based address extraction from images</li>
</ul>


## Built With

_______________________________________________
| Tool/Library   | Purpose                    |
|----------------|----------------------------|
| C++            | Core programming language  |
| SFML           | Graphics, windowing, UI    |
| libcurl        | API requests               |
| nlohmann/json  | JSON parsing               |
| SQLite         | Local database storage     |
| Tesseract OCR  | Image to text OCR          |
| CMake          | Build system               |



## Getting Started


Follow these steps to get a local copy of BestRoute up and running.


## Prerequisites 


Make sure these libraries are installed on your system:
   <ul>
     <li>SFML</li>
     <li>libcurl</li>
     <li>SQLite3</li>
     <li>nlohmann/json.hpp (header-only)</li>
     <li>Tesseract OCR (optional for OCR feature)</li>
     <li>CMake</li>
   </ul>
   You can install them using vcpkg, brew or apt.


## Installation


1. Clone the repository

<code>git clone git@github.com:KristinaRobinson2/BestRoute.git
   cd BestRoute</code>

2. Build the project with CMake

<code>mkdir build
   cd build
   cmake ..
   make
   </code>


   ## Usage


   1. Launch the application:
  
<code>./BestRoute</code>

   2. Features to explore:
      <ul>
        <li>Add stops manually or import from a file</li>
        <li>(Optional) Upload an image of addresses and extract them with OCR</li>
        <li>View the route on a map and optimize</li>
        <li>Get turn by turn directions</li>
        <li>Save or load routes from local storage</li>
      </ul>


## License


Distributed under the MIT License.


## Contact


Kristina Robinson
GitHub: KristinaRobinson2
E-mail: Karobinson2@student.fullsail.edu


## Acknowledgements


<ul>
  <li>SFML (https://www.sfml-dev.org/)</li>
  <li>libcurl</li>
  <li>nlohmann/json (https://github.com/nlohmann/json)</li>
  <li>SQLite</li>
  <li>Tesseract OCR (https://github.com/tesseract-ocr/tesseract)</li>
  <li>Mapbox (https://www.mapbox.com/)</li>
  <li>Google Maps Platform</li>
</ul>

