# Flashcard Django App

## Acknowledgements
- This project is a part of the [Gaza Sky Geeks ](https://gazaskygeeks.com/) Training program.
<p align="center">
<img src="https://gazaskygeeks.com/wp-content/uploads/2020/05/gsg-website-logo-colored-280-50.png" width="40%">
</p>

## Introduction
This flashcard app allows users to create and manage their own flashcards for memorizing new topics and learning new languages.

## Features

- Create a new flashcard by writing a question on the front and the answer on the back.
- The Leitner system is implemented, which sorts flashcards into groups based on how well the learner knows each card. 
- Update an existing flashcard by filling out a form with the editable content.
- Secure data handling with the use of the `{% csrf_token %}` template tag to prevent cross-site request forgery.
- Option to use tags to categorize and organize flashcards.

## Back-end
- The back-end of the application is built using Django (Python Framework)

## Frontend
- The frontend of the application is built using simple CSS for styling and HTML for the structure.
- The dynamic content is generated using Django template code.

## Usage

To use this flashcard app, follow these steps:

1. Clone the repository to your local machine: 
`git clone https://github.com/Mahmoud-Hijjeh/flash_card_app-django.git`.
2. Change into the directory: `cd flash_card_app`.
3. Create a virtual environment: `python3 -m venv venv`.
4. Activate the virtual environment: `source venv/bin/activate`.
5. Install the required packages with `pip install -r requirements.txt`.
6. Apply migrations: `python manage.py migrate`.
7. Run the development server with `python manage.py runserver`.
8. In your web browser, go to `http://127.0.0.1:8000/` to access the app.
9. Create new flashcards, organize them with tags, and test your memory with the Leitner system.

## Notes

- This app is designed for personal use and has not been tested for large-scale deployment.
- This is only a sample implementation and can be further developed and customized to meet specific needs.

## License
This project is licensed under the MIT License.

![التقاط](https://user-images.githubusercontent.com/107920651/218190390-c309593e-fe3a-46bd-b42b-b265357ce543.PNG)
![1](https://user-images.githubusercontent.com/107920651/218190433-6954815e-5122-4fb9-9d70-58c758e8c65c.PNG)
![2](https://user-images.githubusercontent.com/107920651/218190475-be895fc6-b945-4ab4-bcfa-355f44992fc1.PNG)
![3](https://user-images.githubusercontent.com/107920651/218190513-04b204a5-97a5-4dde-92dd-5e5ce2447767.PNG)
![4](https://user-images.githubusercontent.com/107920651/218190533-60ccd9ec-3ce2-4883-bb0d-3c97986a6a65.PNG)
