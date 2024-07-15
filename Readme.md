# TRENGENZ

The TrenGenz feature is a specialized column within our project that focuses on Gen Z trends in fashion. It highlights trending styles accompanied by popular hashtags such as #retrofuturistic and #cottagecore, ensuring Gen Z users stay connected with the latest social trends and hashtags. This feature addresses the Gen Z fear of missing out (FOMO) by providing curated selections of trending styles, fostering a sense of community, and ensuring users feel informed and connected.

## Deployment Instructions
To deploy and use this feature locally, follow these steps:

### Clone Repository: 
        git clone <https://github.com/KAnkita33/IITPatna_Apex.git>
        cd <repository-directory>

### Navigate to Project: 
        cd <project-directory> 

### Setup Environment:
Ensure Python and Django are installed. Create a virtual environment if desired.

### Database Setup:
Run the following commands to set up the database (delete db.sqlite3 to avoid any errors):
        python manage.py makemigrations
        python manage.py migrate
        python manage.py createsuperuser

Follow the prompts to create a superuser (username, email, password).

### Run Server:
        python manage.py runserver
    
Open any web browser and navigate to http://localhost:8000/ or any such link displayed in terminal http://127.0.0.1:8000/ to access the project.

### Admin Panel Setup:
Go to http://127.0.0.1:8000/admin in your web browser.

Log in using the superuser credentials created earlier.

Add products and other relevant data for using the TrenGenz feature.
