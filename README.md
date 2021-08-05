# workoutLogMap-Leaflet
 this project is created using leaflet library is used for more info https://leafletjs.com/ .

NOTE-
1. Allow browser to access your location 
2. view this application using desktop mode (in case of mobile)

Instructions-
1. click on the desired location on the map where you had performed your workout
2. choose the type of workout i.e Running or Cycling  (currently only these, more workout type may be in future updates)
3. now enter the respective data requested by the form and hit enter , now the marker will be visible on the map with short description of workout hovering above it
4. You can add multiple workout using the steps above
5. click the  specific workout label to navigate the map to the location where the workout was performed

Features -
1. Your workouts will be saved to your localstorage so that you can access them whenever you load the application again
2. to clear the previous workout from localstorage perform ,this simple steps
--> hit ctrl+shift+I in your browser to open console
--> type command : app.reset();
-->hit enter and the pervious workout data will be deleted
**soon a new update will be pushed ,that will add RESET button to the UI , till then really sorry
deployment - https://maptymaps.netlify.app/
