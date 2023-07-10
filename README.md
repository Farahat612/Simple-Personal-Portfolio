# Simple-Personal-Portfolio
A simple Personal Portfolio web app using Python, Django and Postgres.

## Project Overview

This project serves as a practice during a learning journey. It allows user to have a personal portfolio where he can share his work.


## Getting Started

To run the website on your local machine, follow these steps:

1. Clone the repository: `$ git clone <repository-url>`
2. Navigate to the project directory: `$ cd <project-directory>`
3. Install the required dependencies: `$ pip install -r requirements.txt`
4. Apply the database migrations: `$ python manage.py migrate`
5. Collect static files: `$ python manage.py collectstatic`
6. Start the development server: `$ python manage.py runserver`
7. Open your web browser and visit `http://localhost:8000` to access the Social media website.


## Usage

- Add your image in the `/jobs/static` directory.
- Adjust the  `home.html` template adding your Name, About and image reference.
- Create an admin user from terminal using command : `$ python manage.py createsuperuser` .
- Run the development server.
- Log into the admin panel and start adding your jobs.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: `$ git checkout -b my-new-branch`
3. Make your changes and commit them: `$ git commit -am 'Add some feature'`
4. Push the changes to your branch: `$ git push origin my-new-branch`
5. Submit a pull request detailing your changes.

## Known Issues or Limitations

Currently, there are no known issues or limitations with this project.

## License

This project is licensed under the [MIT License](LICENSE).
