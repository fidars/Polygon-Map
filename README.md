# Polygon-Map
This Web Application uses Leaflet Js Libraries to draw a polygon over Open Street Map and measures it's area and calculate the nominal solar power that can be generated with the solar installation in polygon.

For Demo: https://fidars.github.io/Polygon-Map/

Steps: 
1. Draw a Polygon with the Measure tool on top right corner
2. Click on Map
3. A pop up shows on the drawn polygon showing the power in W 

Nominal Power or Peak Power is calculated using
  Power = (Solar Irradiance) x Area x (Efficiency of PV) 
    Solar Irradiance under Standard Testing Conditions: 
      1] 25 Degree C
      2] Sun Perpendicular to Earth
      3] Solar Irradiance= 1000 W/ Sq m (Approx)
    Area in Sq m
    Efficiency of PV in % (Consider a value between 14% - 20%)
    
    example: 
      Area= 10 Sq m
      Efficiency: 15% = 0.15
      Solar Irradiance= 1000 W/ Sq m
      
      Power = 1000 x 10 x 0.15
            = 1500 W
    
