## Tech Stack (Dependencies)

1. **Backend Dependencies** - Our tech stack will include the following:
### 1. Backend Dependencies
Our tech stack will include the following:
 * **virtualenv** as a tool to create isolated Python environments
 * **SQLAlchemy ORM** to be our ORM library of choice
 * **PostgreSQL** as our database of choice
 * **Python3** and **Flask** as our server language and server framework
 * **Flask-Migrate** for creating and running schema migrations

You can download and install the dependencies mentioned above using `pip` as:
```
pip install virtualenv
@@ -36,7 +36,8 @@ pip install Flask-Migrate
```
> **Note** - If we do not mention the specific version of a package, then the default latest stable package will be installed. 
2. **Frontend Dependencies** - You must have the **HTML**, **CSS**, and **Javascript** with [Bootstrap 3](https://getbootstrap.com/docs/3.4/customize/) for our website's frontend. Bootstrap can only be installed by Node Package Manager (NPM). Therefore, if not already, download and install the [Node.js](https://nodejs.org/en/download/). Windows users must run the executable as an Administrator, and restart the computer after installation. After successfully installing the Node, verify the installation as shown below.
### 2. Frontend Dependencies
You must have the **HTML**, **CSS**, and **Javascript** with [Bootstrap 3](https://getbootstrap.com/docs/3.4/customize/) for our website's frontend. Bootstrap can only be installed by Node Package Manager (NPM). Therefore, if not already, download and install the [Node.js](https://nodejs.org/en/download/). Windows users must run the executable as an Administrator, and restart the computer after installation. After successfully installing the Node, verify the installation as shown below.
```
node -v
npm -v
@@ -133,13 +134,13 @@ Best of luck in your final project! Fyyur depends on you!


## Development Setup
1. Download the project starter code locally
1. **Download the project starter code locally**
```
git clone https://github.com/udacity/FSND.git
cd FSND/projects/01_fyyur/starter_code 
```

2. Create an empty repository in your Github account online. To change the remote repository path in your local repository, use the commands below to change the Git remote (origin):
2. **Create an empty repository in your Github account online. To change the remote repository path in your local repository, use the commands below:**
```
git remote -v 
git remote remove origin 
@@ -153,7 +154,7 @@ git commit -m "your comment"
git push -u origin master
```

3. Initialize and activate a virtualenv using:
3. **Initialize and activate a virtualenv using:**
```
python -m virtualenv env
source env/bin/activate
@@ -163,18 +164,18 @@ source env/bin/activate
source env/Scripts/activate
```
4. Install the dependencies:
4. **Install the dependencies:**
```
pip install -r requirements.txt
```

5. Run the development server:
5. **Run the development server:**
export FLASK_APP=myapp
export FLASK_ENV=development # enables debug mode
python3 app.py
```

6. Verify on the Browser
6. **Verify on the Browser**<br>
Navigate to project homepage [http://127.0.0.1:5000/](http://127.0.0.1:5000/) or [http://localhost:5000](http://localhost:5000) 
