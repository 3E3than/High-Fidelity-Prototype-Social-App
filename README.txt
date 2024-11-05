###########################################################
## Using the Over Drinks Web App High-Fidelity Prototype ##
###########################################################
IMPORTANT (SETUP FOR USER):
  If you are an instructor testing/grading the prototype, please follow the instructions below to start the prototype:
  1. Clone the repository or download and extract the .zip file onto your local machine.
  2. Navigate to the over-drinks directory - the directory should contain this very README file.
  3. Open a terminal window and navigate to over-drinks directory, and verify this through ls -al, and look for README.txt
  4. Then, execute the following command: python3 -m http.server 
  (some machines may call python using "python")
  5. Depending on your operating system, you may be prompted with a security warning or message - make sure to allow the permissions it is asking. 
  6. The terminal window can now be minimized. To start running the prototype,go to http://localhost:8000 on your browser and click on LoginScreen2.html (same directory as README.txt)
  7. From there, all the pages can be traversed through links and buttons in the prototype.
  NOTE: to preserve functionality, it is best not to access pages by opening them directly. 
  WARNING: The AI functionalities of the prototype may not be supported anymore due to insufficient credits on rea.gent, the web platform that was used to enable AI recommendations.

################################################################################################
## The information below is not necessary or relevant to setting up the prototype for grading ##
################################################################################################
  Web-Based - Due the usage of the insecure localStorage API, it is NOT recommended to provide real information when email, 
  username, or password are prompted from the user. If you wish to deploy this prototype in a web-based application, the
  repository can be cloned or downloaded as a .zip file, then the over-drinks folder can be uploaded to your website. To ensure
  normal flow of the application, make sure the user starts at LoginScreen2.html. 

  For optimal Functionality, please use the latest version of browsers that are currently being actively updated, like Chrome, Firefox, Edge, Opera, Safari, etc. 
  In addition, ensure that you have internet access while the app is being run so the Bootsrap dependencies, as well as the LLM backend remain functional and 
  do not break app appearance and function.
