# Task-Management-System
Task management project

                 Task Management App run process

Prerequisites:
1.Python: Ensure Python is installed on your system. You can download it from the official Python website.
2.MongoDB: Install and run MongoDB. You can get MongoDB from the official website.
Steps to Run the Task Manager App:
1.	Clone or Download the Project:
Clone the project repository from your version control system (e.g., GitHub) or download it as a ZIP file and extract it to a folder on your computer.
       2.  Set Up Virtual Environment (Optional but Recommended):
Create a virtual environment to isolate your project dependencies. Open a terminal or command prompt and navigate to your project directory:
cd path/to/your/project
python -m venv venv
venv\Scripts\activate

3. Install Python Dependencies:
Install the required Python packages using pip. In your project directory, run:
pip install -r requirements.txt
4. Start MongoDB:
Start your MongoDB server. Run the MongoDB daemon by executing mongod in a terminal or command prompt.	
5. Configure the Application:
•	Open the Flask app file (app.py or similar) and ensure the MongoDB connection settings are correctly configured (e.g., database name, host, port).
•	Ensure the frontend files (HTML, CSS, JavaScript) are properly linked and are using jQuery to communicate with the Flask API endpoints.
6. Run the Flask Application:
Run your Flask application. In the terminal or command prompt, navigate to your project directory and execute:
python app.py
This command will start your Flask application. You should see output indicating that the app is running on a specific host and port (e.g., http://127.0.0.1:5000/).
8. Interact with the Task Manager App:
•	Register a new user or log in with existing credentials.
•	Explore the functionalities provided by the app, such as adding tasks, viewing tasks, updating tasks, or deleting tasks.
•	Ensure that the data is properly stored in the MongoDB database and retrieved/displayed correctly on the frontend.

Notes:
•	Ensure that MongoDB is running while the Flask app is active to facilitate database operations.
•	Debug any issues related to API endpoints, database connections, or frontend functionality by checking logs and debugging tools provided by Flask and your browser's developer tools.
•	Ensure you save one user as admin manually in DB to access the Admin page.
•	After Registration press Login option from navbar to login of the user or admin.
•	First view the task then press edit to edit the task.  






