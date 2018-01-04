# GitCommitHistory
This Application will grab all the commit data from last 1 year of a particular repository by using Username and repository name and and will represent in a graph.


Steps followed for this :

STEP 1 : By using Postman tool and Git Hub commit history API, I have generated a response in which each week has been given an id and the number of commits done on each day is acquired in a JSON format.

STEP 2 : By employing scripting languages I converted the weekly input to months.

STEP 3 : I have then used Google Charts for Visualizing this data onto a graph.

STEP 4 : I have created a text field where users can input the repository address and the GIT API will retrieve the Commit history data from given address and visualize them in a Chart.

For more detailed discussion about this application,  email me at manohar.22r@gmail.com.

Note : By default, this code will take tensorflow/tensorflow/ as address. You can give alternate address in the text bar provided in the top and CLick Generate button!

The Screenshots of default response (Tensor flow) and New address (manoharreddy2343/GitCommitHistory) are also uploaded. Please find them.

Also, I am attaching  the response I got using postman tool as response.json.

