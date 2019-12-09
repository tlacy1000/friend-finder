# friend-finder 
Friend-finder is an app that matches friends via compatibility survey using node and express. A user answers ten questions based on big 5 personality psychology and is matched with a teen titan who they would get along with well based on reverse scoring and complementary trait matching. The question format utilizes a likert scale with response options ranging from 1 (Strongly Disagree) to 5 (Strongly Agree).


#Demo
Friend Finder is deployed to Heroku. Please check it out here.

#Installation
To install the application follow the instructions below:

#git clone https://github.com/tlacy1000/friend-finder.git
cd friend-finder
npm install
Running Locally
To run the application locally and access it in your browser, first set the PORT environment variable to the value of your choice. An example is shown below.

export PORT=
After the PORT environment variable has been set, run the Node.js application with the command below.

node server.js
The application will now be running locally on PORT, in this case that is port 3030. You can then access it locally from your browser at the URL localhost:PORT, in this case localhost:3030.
