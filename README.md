The main application consists of 2 main components: a centralized RESTful API and a companion web app. 

The API will be a clean extensible interface that provides multiple endpoints for getting 
- Authentication
- Beat information (constables assigned, etc),
- Reporting information (Potential crimes, risks, etc), 
- Management services (assigning a constable, risk assessment), 
- Transformation and filtration of data for visualization.

The client side will be split into 4 parts:
- Visualization objects: Latest risk related data is plotted onto various heatmaps, graphs and lists which indicates the status of beats. 
- Management: Ability for a Station House Officer to assign and re-assign policemen to a beat.
- Timeline: Past cases, crimes etc that can be filtered by beat, time etc.
- Reporting: A form will be submitted by the constable regarding information of a beat and an associated color (green, yellow, red) to indicate the current state of the beat.
