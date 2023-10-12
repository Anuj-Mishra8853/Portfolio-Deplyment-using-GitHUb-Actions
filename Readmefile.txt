step 1: Push the Portfolio file to Github
step 2: login to aws account and create s3 bucket 
step 3: create a .github/workflow folder and inside create a main.yaml file for actionfile 
	take the actionfile from repository
step 4: For credentials go to aws account and in IAM create user and provide permissions for s3 
	necessary permissions only 
step 5: Go to GitHub repository settings and select secrete and variables and create a new repository
	access key and paste both keys and ID-key in it with a same name of action.yaml credentials 
step 6: Now to go the s3 bucket and paste the policy and allow the static hosting in permissions
step 7: Action file automatically run and in s3 static hosting click the link to see the website
