Top View and Selecting of Layers
--------------------------------

Selection and display of different data in the Top View with the help of the layer chooser.

  .. video:: ../_static/mp4/tutorial_wms.mp4
     :alt: When we open the Top View (CTRL+H) of the map, the Web Map Service is already opened by default.
           It collects its data from the server: "open-mss dot org" that provides demodata for the meteorological or
           atmospheric informations as layer lists.
           As we click on the "server layer" option, the layer list window opens that lists out various layers.
           We just have to enter the WMS url and get capabilities for those layers.
           So, here we find various layers: Divergence and Geopotential Height,
           Equivalent potential temperature and geo potential height, etc.
           When we click on the "Divergence" layer, some divergence in height that are marked by blue and
           red lines are displayed.
           Similarly, when we move on to the "Equivalent potential temperature" layer,
           we find various temperature potentials at various places on the map.
           We can also customize the levels, that is, the pressure levels after selecting a particular layer.
           As we enter "temperature" in layer filter, all the relevant layers related to temperature are displayed.
           In multilayering, we can see more than one layers such as temperature and pressure together
           at the same time displayed onto the map.
           Suppose we are using any layer frequently, we can just star it and find it easily using layer filter.
           Now coming to "Divergence and Geopotential Height", we can check the map at various atmospheric pressures such
           as at 150 hPa or 200 hPa or 500 hPa.
           Initialisation shows the date and time from which the data is available. Here it is 17/10/12.
           Valid shows the date and time till the data available is valid.
           Here it is 17/10/12 and time is 12:00 UTC.
           We can customize these points as per our requirement.
           We can select the various initialization and valid interval slots as per availability.
           For example, when we select 3 hours initialization time, we can see the date and time marked crossed
           as there is no such initialization time ahead or back.
           Similarly, when we select 6 hours valid time we can see the time changes to 18:00 UTC.
           Coming to the auto-update, if it is checked then whatever is selected on the list gets updated on
           the map automatically.
           If the "auto update" option is not checked then we have to press retrieve after
           each selection on the layer list.
           If we select "use cache" as checked, then it takes less time to load the data from layer list
           on the map but if its unchecked it takes more time to load.
           We can also click on "clear cache" to clear the cache that is stored locally for the layer lists data.
           There is a "delete trashcan button" on the top left corner of the layer list to clear all the
           layers loaded from the server.
           Clicking on remove deletes the layer data on the map.
           Now we close the WMS layer list window.
