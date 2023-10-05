This is a simple Django Todo application with Continuous Integration and Continuous Deployment (CI/CD) set up. It allows you to Create, Read, Update, and Delete tasks.

**Prerequisites:**

AWS account.

Python & Django.

Git & Github.

Jenkins.

Docker.

**Features:**

Create, Read, Update, and Delete tasks.

Mark tasks as completed or pending.

Continuous Integration and Continuous Deployment (CI/CD) pipeline configured for automatic deployments.

**Setup:**

Follow these steps to set up the project locally:

To get this repository, run the following command inside your git enabled terminal:

$ git clone https://github.com/Rohit123890/django-todo-cicd.git

You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command:

$ python manage.py makemigrations

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command:

$ python manage.py migrate

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user:

$ python manage.py createsuperuser

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command:

$ python manage.py runserver

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers and Happy Coding :)
