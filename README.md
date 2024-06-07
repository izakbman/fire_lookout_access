# Tower Access

## Author 
Izak Boardman 
iboardma@uoregon.edu

### Overview
Tower Access is an application designed to help users find open roads and public land with access to fire tower lookouts throughout Oregon. The application identifies fire tower lookouts that can be accessed through roads not blocked by gates or private land, enhancing the experience for outdoor enthusiasts, overlanders, hunters, and adventurers.

#### Features
Mapping Fire Lookouts: Visual representation of fire tower lookouts across Oregon.
Road Network: Includes public and private roads, highlighting those that provide access to fire towers.
Land Boundaries: Distinguishes between public (BLM, USFS) and private lands to avoid trespassing and plan safer routes.
Roads & Land Boundaries:
OpenStreetMap
BLM Management Ownership Polygon Hub
Fire Towers:
Data sourced from https://bestmapsever.com/pages/oregon-fire-lookouts-list
Usage: Install requirements for map.ipynb. map.ipynb can be used to view the different filtered datasets as well as plots. All of the project functionality is currently contained in map.ipynb

OpenStreetMap data and BLM data should be processed and stored in the data/ directory.
#### Next StepsL 

Data Integration and API Development: Integrate geospatial data into a spatially optimized database like MongoDB. Develop an API for dynamic data querying.
Frontend Development: Create an interactive web interface using frameworks like React or Vue.js and mapping libraries like Leaflet or Mapbox GL JS.
Routing and Navigation: Enhance the backend to support route calculation, integrating with routing engines like OSRM or GraphHopper.
Real-time Updates and Alerts: Implement a system for real-time updates on road conditions, closures, and weather conditions.
User Contributions and Feedback: Enable user-contributed data, such as reporting road conditions or closures.
Permitting and Access Information: Integrate land access permits into the platform for seamless user access.
Optimization and Scalability: Optimize performance and ensure scalability.
Mobile Application Development: Develop a mobile application to provide on-the-go access to maps and real-time updates.

#### Acknowledgments
OpenStreetMap contributors
BLM Management Ownership Polygon Hub
For more details, visit the project's GitHub repository.

Feel free to contribute, report issues, or suggest improvements!