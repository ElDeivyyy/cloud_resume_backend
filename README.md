This guide will help you set up the backend for the Cloud Resume Challenge project, even if you're new to it.

WALKTHROUGH

REQUIRED SOFTWARE
1. Install Git
2. Install Python:
- Download and install Python from python.org. Make sure to check the box to add Python to your PATH during installation.
3. Create a new folder on your computer where you want to keep your files.
- You can name this folder "Cloud_Resume_Challenge".

REPOSITORIES
1. Open the command line.
2. Use the command cd path/to/your/folder to change to your project folder.
- Replace path/to/your/folder with the actual path.
3. Clone the Repository:
- Use the command git clone git@github.com:YOUR_USERNAME/cloud_resume_backend.git.

CREATE .gitignore FILE
1. Open Your Project Folder.
2. Create a .gitignore File:
- Right-click inside the folder, select "New," then "Text Document."
- Rename the file to .gitignore (make sure to remove the .txt extension).
- Open the file and add the following lines:
venv/
pycache/
*.pyc
*.pyo
3. Save the file.

SET UP THE BACKEND
1. Create a Virtual Environment:
- In your command line, navigate to your project folder.
- Type python -m venv venv and press Enter. This creates a virtual environment named venv.
- Activate the virtual environment:
# On Windows: Type .\venv\Scripts\activate and press Enter.
# On macOS/Linux: Type source venv/bin/activate and press Enter.
2. Install Required Packages:
- Type pip install -r requirements.txt to install all necessary packages listed in the requirements.txt file.
3. Create or Edit the Main Backend File:
- Open the lambda_function.py file or create a new one if necessary, using a text editor. This is where you will write your backend code.

INITIALIZE GIT AND PUSH CHANGES
1. Open Command Line.
2. Stage Your Files:
- Type git add . to add all files to Git.
3. Commit Your Changes:
- Type git commit -m "Initial commit for backend" and press Enter.
4. Add the Remote Repository:
- Type git remote add origin git@github.com:YOUR_USERNAME/cloud_resume_backend.git and press Enter.
5. Push Your Code:
Type git push -u origin master and press Enter
