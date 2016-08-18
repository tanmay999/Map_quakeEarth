###MAP_quakeEarth application
        
        MAP_quakeEarth is  a java GUI(Graphical User Interface) Application totaly developed in ECLIPSE. It has an important significant feature to display  the  places or rather Location in World  where Earthquake has happened in past Graphically on the WorldMap.we have impoted java.util package along with Unfolding Maps package in order to develop apllication on worldmap.This application uses Point Markers from the package(UnfoldigMaps) automatically of different colours,shapes and size in order to mark the earthquakes according to their magnitude,location,demography,is on Land or Water,etc.
           
           
           This application also displays a Label describing  the latitude and logitude of the location,city name,population,country etc of the earthquake location pointed to by the cursor using EventHandling concept of java.
           It also shows various cities in the world map.It also has great feature of event dispatcher by which we can move the map left ,right or magnify any tiles of the map by just double click of the mouse button.This creates greater efficiency,precision and realistic view of the world map.
           
           ![screenshot 22](https://cloud.githubusercontent.com/assets/18321499/17771374/37b0a93e-6560-11e6-8f28-488a32852a8e.png)
           
           
                                This application when executed it it automatically loads the current WorldMap bythe given
        url: "earthquakesURL = "http://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/2.5_week.atom" if there is internet connection.If there is no internet connection provided then users do not need to worry .There is an offline if else condition already coded for this criteria.
        
        
                          /*      if (offline) {
		    map = new UnfoldingMap(this, 200, 100, 700, 500, new MBTilesMapProvider(mbTilesString));
		    earthquakesURL = "2.5_week.atom"; 	// Same feed, saved Aug 7, 2015, for working offline
		}
                        */.
                      
                      
                   earthquake magnitude aswell as location data is taken from the database  in the link provided below
                   
                   // earthquakesURL = "http://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/2.5_week.atom"//
                        
                        !
                        
                        
![screenshot 22](https://cloud.githubusercontent.com/assets/18321499/17771374/37b0a93e-6560-11e6-8f28-488a32852a8e.png)
                        
                          any further enhansment to this project  is welcomed and would be futher appreciated  .
