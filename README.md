1. Title & Purpose	::: Solving the Logistics Mapping Challenge: Integrating Google Locations with Pin Codes in India
2. Problem statement ::: The logistics operations use Google locations for internal movement of goods, but the external serviceable areas are represented by pin codes. With no direct relationship between Google locations (latitude and longitude) and pin codes, a solution is needed to align these two systems.
4. Feature	::: 
         a) Data Collection: Gathered Google location lat-long data and block office pin code lat-long master data.
         b) Distance Calculation: Calculated the Euclidean distance between each Google location and block office.
         c) Mapping: Tagged each Google serviceable location with the nearest pin code where the Euclidean distance was minimum.
         d) Refinement: Utilized a recursive process to ensure accurate one-to-one mapping by finding the minimum distance.
6. Usage	::: This solution allows to efficiently align Google locations with pin codes, enhancing logistics operations and providing clear serviceable areas to external stakeholders.
7. Tools Used	::: Python,Euclidean distance,latitude-longitude mapping
