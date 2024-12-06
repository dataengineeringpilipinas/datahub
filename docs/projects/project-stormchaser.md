---
title: "Stormchaser"
author: "TreacherousDev"
date_created: 2024-11-28
last_updated: 2024-12-03
version: v0.2.2 (beta)
status: Completed
tags: 
  - tropical storm
  - animation
  - typhoon
  - cyclone
  - hurricane
data_sources:
  - "agora.ex.nii.ac.jp/digital-typhoon/"
  - "https://ncics.org/ibtracs/index.php?name=YearBasin-2020"

alignment: "Briefly explain how your project aligns with DEP Data Hub objectives"
---

# Project Stormchaser

*Note: To view the full metadata for this project, please see the raw file in our [GitHub repository](https://github.com/dataengineeringpilipinas/datahub/tree/main/projects).*

## Summary
Project Stormchaser aims to bridge the gap between data and action by providing an interactive visualization tool for understanding tropical storm behaviour. At its core, the app collects typhoon data through web scraping, processes the information, and animates the paths that they take in synchronous time.  Project Stormchaser democratizes access to critical weather information, which is often too technical for ordinary citizens to interpret, by giving them a more intuitive visualization of a typhoon’s movement and intensity. 

## Methodology
Data scraping was done in python using `Beautifulsoup4`. Data about its wind speed, pressure and coordinates at recorded times are collected and arranged into a data structure that gets fed into an animation engine. This engine then runs a simulation that visualizes the typhoon paths synchronously.
The map was drawn using `Cartopy`, drawing land and ocean borders, and many other geographical features. `Pygame` was used to render the scene and display visual output, which are all drawn and animated procedurally.

## Key Findings
The Philippines is located at the heart of the world’s most active tropical storm basin, experiencing over 20 storms each year. Despite the frequency and intensity of these storms, many Filipinos struggle to understand the technical data used to describe them. Project Stormchaser becomes highly relevant in light of recent events, where we saw Northern Luzon experience six consecutive tropical storms back to back in less than a month.

## Visualizations
![11261-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/eb3d1328-e84d-424f-8b38-c1753caaf35b)

## Code
The main repo can be visited [here](https://github.com/TreacherousDev/Stormchaser), which includes an [app version](https://github.com/TreacherousDev/Stormchaser/releases) as a Windows executable.

## Challenges and Solutions
At its core, creating an amination engine from scratch is difficult as it requires deep understanding of vectors, trigonometry and interpolation. A lot of low level math was involved in order to draw the icons, make sure that the objects move at a constant speed along their path from point A to point B, blend the icon colors as they strengthen or weaken into different categories, and all of the other little details that enhance its visual appeal like the landfall detection markers and fade-in fade-out effects.

Web scraping also had to be custom written and tailored to have a navigation system that reflected the source website's paging hierarchy and paging content structure. Data from the tables then had to be cleaned before extraction, as they had to first follow the correct data types and data structures before they get fed into the animation engine. Date / Time had to undergo restructuring and compromises had to be made for missing information within the data, using a technique of copying a cells's vertically adjacent neighbor's data value if the current cell is empty.

The user interface proved to be another hurdle and it is one I haven't completely conquered yet. It is at a state where it is fully functional as a standalone Windows application but is lacking in important features like window scaling and fullscreen mode. This I hope to work more on in future releases.

## Community Impact
Project Stormchaser is more than just an app; it’s a learning tool for anyone interested in how data and technology can help us understand complex topics like tropical storms. It invites people to see how things work under the hood, encouraging them to learn and even improve upon it.  
For end users, the app simplifies the technical data about tropical storms into clear, easy-to-understand visuals. This makes it easier for everyone—from students to families—to grasp how storms move and change, instead of relying on static inforgraphics or isolated animations. By bridging the gap between complex data and everyday understanding, Project Stormchaser makes critical information accessible to all.

## Future Work
- Implement window scaling, fullscreen mode, and interactive overlays for additional information (e.g., affected areas).
- Data inclusive visuals like tropical storm track paths
- Compatibility with other platforms like Mac and Linux

## Contributors
- [TreacherousDev](https://github.com/TreacherousDev)
- [cian0](https://github.com/cian0)

## License
Project Stormchaser is released under the MIT License.
