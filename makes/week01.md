# Week 1 – Reverse Engineering

Project Chosen: Photogrammar - https://photogrammar.yale.edu
## What Is Being Made?
This project is an interactive map and a searchable archive of historical photos. It allows users to click on a specific county in the US and see exactly what life looked like there during the Great Depression and WWII eras.

## What Is the Project Made From? (Data)
The project uses about 170000 photographs from the Library of Congress. These were originally taken by government photographers (FSA-OWI) between 1935 and 1944. Not every photo is on the map. If a photo didn’t have a specific location written down in the original notes, the system can’t place it.

## Tools, Algorithms, or Systems
The project uses Leaflet for the maps and Carto for the database. It uses automated recommender systems and computer vision to suggest related photos and sort images by color or content. While the map updates automatically, the way photos are grouped into categories follows a specific classification system from 1942.

## Human Labor & Decisions
A team at Yale, led by Lauren Tilton and Taylor Arnold, cleaned the messy date from the Library of Congress. The team chose to use a 1940s classification system to group photos into themes like “Work” or “The Land”, which shapes how we interpret the history today.

## Design as Argument
The site uses dots in the center of counties to show photographers moving across the country. It shows that the government’s project was national by showing the dots spread across the entire US. The dots can be deceiving because they make it look like a photo was taken in the exact center of a county, when it might have been taken anywhere in that area.

## Reflection (excerpt)
In this project, “making” isn’t taking the photos but about re-coding them. The researchers took a large, messy dataset and turned them into a visual representation. When machines participate, we get to see the big picture of 170000 images at once. However, if a photo does have a right metadata, the machine makes it invisible on the map. This shows that machines don’t just show data but filter it. The machine requires clean data, meaning the messy parts of history-photos with lost notes- are often excluded. Even though the final product feels automated and objective, it is built on human labor and judgment. From the 1942 classification system to the code that decides where a dot goes, humans still shape what we see. 

