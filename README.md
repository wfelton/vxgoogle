# vxgoogle
VX to Google API
In order for this code to work, you will need to set your client_id and client_secret in the script properties
You will need to set up the OAuth application in VX to get these values
This script is a bound script so you need to open the script editor from a google sheet

The four files are as follows

vxAPI: The three primary functions used to execite the API calls. 

mainCode: The apps script that manages calling the API functions, handles all writing to the Spreadsheet. Also has a few helper functions

userInterface: simple code that makes the menu and manages user input

tokenObj: required for the code to run. Just a simple object to contain token information
