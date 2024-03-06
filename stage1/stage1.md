Miguel Candido Aurora Peralta<br>
VIP Project: Transformative AI for Safety<br>
Project Title: Precipitation and Tucson Traffic Accident Frequency

## Stage 1: Accident Mapping
The first stage of the project will be the visualization of historical traffic accident data. The visualization will be in the form of a map of the City of Tucson showing the locations where traffic accidents occurred. The map can be filtered to show accidents by amount of precipitation, such as accidents that occurred at precipitation levels between 0 and 1 inches. 

The goal of this visualization is to show the areas where the most accidents are occurring. The filter will allow users to compare the accident hotspots when precipitation is and is not occurring.

The first stage is planned to be completed as a deliverable that can be presented at the VIP project showcase on March 23, 2024. 

## Possible challenges
- Rain often does not last for the entire day. How will accidents that occurred on a day with precipitation but not necessarily during the precipitation be handled?
- How will a large number of accidents in a small area be visualized? Color coding?

## Procedure
1. **Data Acquisition**
    - Get City of Tucson and NOAA datasets.
    - Necessary info:
        - Accidents: Location, date, time
        - Weather: Precipitation levels, dates, times
2. **Data Preprocessing**
    - Handle missing values, irrelevant/unnecessary columns.
    - Convert columns to standard and appropriate formats.
3. **Map Visualization**
    - Plotly library
    - Plot accident locations on map using latitude and longitude data.
    - Display City of Tucson boundaries, streets, and major features on the map.
4. **Precipitation Level Filter**
    - Add a user interface in the interactive visualization that allows the user to select precipitation values to filter by. Show maximum value for the time period and prevent users from searching outside of the minimum-maximum range. 
    - Implement filter functionality by filtering accident dataset based on dates/times matching NOAA data.
    - Display filter range overlaid on the map for clarity when screenshots are taken of the visualization for final paper and posters. 
5. **Visualizing Accident Hotspots**
    - Not completely sure yet how the map will handle many accidents occurring in a small area. 
        - Maybe opacity will be low for a single accident so that they'll stack and make the color darker?
    - Would also be useful to generate another separate visualization that's some kind of chart showing the most dangerous areas.
6. **User Interaction with Map**
    - Zooming, panning, resetting
    - Possibly some kind of tooltip or popup option when hovering over accident markers? 
    - Possibly a **time period filter**. Need to analyze time period of entire dataset before making decisions about scope to ensure there will be enough data of consistent quality. 
7. **Documentation and Interpretation of Results**
    - Need some kind of writeup of results for 3/23 showcase poster.
    - Finish readmes
8. **Deployment**
    - How can model be interacted with by potential users? Web app? Something to do with Github? Need to do more research here. 
    - Possible link to model or just code on showcase poster. 
