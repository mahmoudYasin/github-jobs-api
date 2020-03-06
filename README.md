# Github jobs API's Testing

This project created to test the Github jobs APIs using the Postman API testing tool.

This project includes many test cases to cover all scenarios for Github jobs APIs that have description, location, lat, long, page, and full_time parameters. 

Also create test cases for getting the job by ID API with markdown parameters, on this API there is an issue while I tried to send markdown false the API return description and how_to_apply fields and this is not as the GitHub documentation says and they should not return in the API response.


There are negative test cases in the collection file, so if you want to run them all, the script will not complete the test run, because there are many fail test cases.

Also, there are conditions for each API (Test Case) to check the response code and response time in the test tab.

To run the automation script successfully, you have to unselect the negative test cases T_C(4,5,27,28,29,30).

## Getting Started & Prerequisites

Install the Postman Tool.

You have to import the collection file ```GitHub Jobs API's collection .postman_collection.json``` by clicks on the import button at the top of the Postman screen after that drag and drop the file or click on choose file button then click on upload.

You have to import the environment file ```API environment .postman_environment.json``` by clicks on the settings icon in the right of the screen after that click on import button then click on the choose file button from the pop-up.

Finally, choose the uploaded environment from the dropdown list on the top of the screen.

## Running the tests

To run the test, navigate to the collection, of the left of the screen, then click on the arrow icon and then click on the run button.

After collection Runner screen opened, Select the needed APIs that you want to test, after that choose the uploaded environment and customize your collection settings (Optional).

Finally, click on the Run button.

## Authors

* **Mahmoud Yasin** 
