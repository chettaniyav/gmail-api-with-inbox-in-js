# gmail-api-with-inbox-in-js

# JavaScript Quickstart 
Complete the steps described in the rest of this page to create a simple JavaScript web application that makes requests to the Gmail API.

# Prerequisites
To run this quickstart, you need the following prerequisites:

- Python 2.4 or greater (to provide a web server)
- A Google Cloud Platform project with the API enabled. To create a project and enable an API, refer to Create a project and enable the API
- Note: For this quickstart, you are enabling the "Gmail API".
- Authorization credentials for a desktop application. To learn how to create credentials for a desktop application, refer step 2.
- A Google account with Gmail enabled.
# Step 1: Set up the sample
- To set up the sample:

  In your working directory, create a file named main.html.
  Copy the main.html code in your file.  
  
  
# Step 2: Generate the Client ID and API Key: 
          Follow this link- https://developers.google.com/workspace/guides/create-credentials
          
          
# Step 3:  Add Client ID and API Key:
            In the code, replace **************YOUR_CLIENT_ID************** with the client ID you created on google coud.
            In the code, replace *************API_KEY************* with the API key you created as a Prerequisite for this quickstart.
    
# Step 4: Run the code with python:
          To run the sample:
          Start the web server using the following command from your working directory:
          - Python 2.x -> python -m SimpleHTTPServer 8000            

          - Python 3.x -> py -m http.server 8000
          A popup will be shown when clicking authorise select your email id and mails will be loaded.
          I have set the mail to be 10 you can set it to any number you wish.
          You can add multiple test id in google cloud for testing it on different mails.

