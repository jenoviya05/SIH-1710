# Smart India Hackathon Workshop
# Date: 26.10.26
## Register Number: 212225040151
## Name: Jenoviya D
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea

RailNav is an intelligent railway station navigation system that enables passengers to locate facilities and navigate stations easily using interactive maps, shortest-path routing, and step-by-step directions. It provides accessible route planning, voice assistance, multilingual support, and real-time facility updates through a user-friendly platform, improving passenger convenience and accessibility.

## Proposed Solution / Architecture Diagram

RailNav is a smart railway station navigation system that helps passengers easily locate platforms, ticket counters, restrooms, food courts, waiting halls, lifts, and exits. It provides interactive station maps, step-by-step directions, and shortest-path navigation to reduce confusion and save time. The system supports accessible routes for passengers with disabilities, voice-guided navigation for visually impaired users, and multilingual assistance. Railway staff can update facility information and temporary route closures to help passengers receive accurate directions. The system can be accessed through a mobile-friendly web application and digital kiosks.

<img width="1066" height="1584" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/e4a625dc-d438-4fc9-9e33-d3f2e669cb1a" />



## Use Cases

Facility Location: Passengers can search for ticket counters, restrooms, drinking water, food courts, ATMs, waiting halls, enquiry counters, and other facilities within the station.

Platform Navigation: The system guides passengers from the station entrance to their required platform using step-by-step directions and the shortest available route.

Accessible Navigation: Wheelchair users and passengers with mobility difficulties can select accessible routes that prioritize ramps, lifts, and step-free pathways while avoiding stairs and inaccessible paths.

Voice-Guided Navigation: Visually impaired passengers can receive spoken directions to navigate station facilities independently.

Multilingual Assistance: Passengers can access navigation instructions in supported languages, helping users who are unfamiliar with the local language.

Real-Time Facility Updates: Railway staff can update facility availability, lift closures, blocked pathways, and temporary diversions so that passengers can receive alternative directions.

Digital Kiosk Navigation: Passengers without smartphones can use touchscreen kiosks to search for destinations and view directions.

Offline Navigation: Previously downloaded station maps and essential facility information can help passengers navigate when internet connectivity is unavailable.

Emergency Exit Guidance: The system can display verified emergency exits and authorized evacuation routes based on station safety information.

Passenger Convenience: By providing clear directions and facility information, RailNav helps reduce unnecessary walking, confusion, and delays when navigating unfamiliar railway stations.


## Technology Stack

The frontend is developed using HTML, CSS, JavaScript, and Bootstrap to provide a responsive and user-friendly interface. Python with Django is used for backend development and route processing. SQLite stores station maps, facility locations, and navigation data. Leaflet and OpenStreetMap provide interactive maps, while Dijkstra's shortest-path algorithm calculates routes between station locations. Browser Text-to-Speech provides voice instructions, and JavaScript Fetch API enables communication between the frontend and backend.


## Dependencies

The project requires Python 3.x, Django, SQLite, HTML, CSS, JavaScript, Bootstrap, Leaflet, and an internet connection for loading online map tiles. Station floor plans and facility coordinates are required to create accurate indoor maps. Browser Text-to-Speech support is required for voice navigation. Additional dependencies such as QR codes or Bluetooth Low Energy (BLE) beacons can be used for indoor positioning. Real-time facility updates require a backend interface for authorized railway staff, while integration with railway services requires access to the relevant APIs.
