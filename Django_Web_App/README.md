# Smart_Farm_Django_Web_App

# Create a virtual environment (you can name it 'venv' or anything you like)
python -m venv venv

# Activate the virtual environment
# On Windows
cd djangoWebProject
.\venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate


# Install required packages from requirements.txt
pip install -r requirements.txt


# Make migrations based on your models
python manage.py makemigrations

# Apply migrations to the database
python manage.py migrate


# Create a superuser to access Django admin
python manage.py createsuperuser


# Run the development server
python manage.py runserver

----
execute program python manage.py runserver YOUR_IP:PORT
YOUR_IP : ipconfig
----


# Go to the Django admin page
http://YOUR_IP:PORT/admin/



# mqtt subscription 
micro&objetsconnecte_Proj\Smart_Farm_Django_Web_App\djangoWebProject>
python -m smartFarmapp.mqtt