**Assignment Overview** -<br>
Build a program for running NextBillion APIs - Map Rendering+Search (from current location- hard coded as 3b2 mohali my native place)+ Routing to the searched location (origin location - curent location hard coded 3b2 mohali and Destination - the searched POI result)

**Assumptions** - <br>
API key used in this program as provided by the NB team <br>
HTML used for rendering the map tiles + for the search box + for locating the near by searched POI <br>
current location hard coded as - 3b2 mohali, since its web application <br>
created marker with help from next billion documentation- default style  <br>
Hit the search API using javascript fetch method <br>
considered the first outcome from the overall 20 results of POIs response (via search API) for the marker and final POI for rendering on the map tile 
which is further considered for the routing destination (considering the origin as - hard coded current location of 3b2 Mohali, Punjab, India) <br>
If you are not familiar with 3b2 Mohali locality, please search for places as such - "Gopal Hospital", "Liberty Hospital", "Cafe Coffee Day"and "Max Hospital" etc <br>

**Demo Run Workflow** - <br>
Please type "Gopal Hospital" in the search box and hit the Search button to locate on map <br>
Further Hit the "Request Direction" button to get the routing direction <br>
You would observe the ETA's & Distance parameter in the last dialog box <br>
