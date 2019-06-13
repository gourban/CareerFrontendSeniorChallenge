#goUrban Senior Frontend Developer Challenge

General Instruction:
Please use ReactJS and Redux for this challenge. Our Test-API will be available for this challenge. We will take a look especially on the architecture of the project.

API calls:
Please set in the header Accept and application/json.

Task:
Create a basic dashboard with two screens. One screen is a map (you can use any map framework of your choice) and draw markers (without any style provided through the framework) on the map that show the position of vehicles. You can retrieve all vehicles from https://core.staging.gourban.eu/front/vehicles?branchId=3. Use the location parameter to get the right coordinates.
The second screen is a table view (use please ant table) to show this vehicle within the table. Please show: id, license plate, location as pure text (no links). If you click on a vehicle in the table, you should be routed on the first screen with the map and the marker of the selected should be highlighted.

Hints:
- Please be careful how often you render the markers on the map
- Design does not matter and will not be rated but basic styling should be done.
- Add a autorefresh every 30 seconds to get new vehicle data.
