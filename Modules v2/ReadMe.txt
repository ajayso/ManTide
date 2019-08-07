Please note ...

To run these python commands , you must first register your client to connect to Google SQL instance.
You can do this in the SQL Dashboard of GCP. 


Make sure that your IP is allowed to connect to this instance. 

User : Savinay
Pass : savinay


#######################################################################################################


Two main Modules :

1) Model Selector Target:
	
	It selects the best model for prediction among the applied DL models , Refer Docstring.
	It returns a Token which implies the best model
	
	Assumed to be run on a weekly basis.

2) Learnet Target :

	It trains the model with the target industry's historical ( which has to be provided ) on the 
	token recieved by the Model Selector.
	
	Assumed that this will run daily after market closes.

A visual representation how modules interact with one another using a Acyclic graph will be sent to ajays@morningblaze.com 
if required.


#########################################################################################################

To be deployed and Tested.
