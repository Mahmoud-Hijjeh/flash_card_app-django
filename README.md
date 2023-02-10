# Flashcard Django App

This flashcard app allows users to create and manage their own flashcards for memorizing new topics and learning new languages.

## Features

- Create a new flashcard by writing a question on the front and the answer on the back.
- The Leitner system is implemented, which sorts flashcards into groups based on how well the learner knows each card. 
- Update an existing flashcard by filling out a form with the editable content.
- Secure data handling with the use of the `{% csrf_token %}` template tag to prevent cross-site request forgery.
- Option to use tags to categorize and organize flashcards.

## Usage

To use this flashcard app, follow these steps:

1. Clone the repository to your local machine.
2. Install the required packages with `pip install -r requirements.txt`.
3. Run the development server with `python manage.py runserver`.
4. In your web browser, go to `http://127.0.0.1:8000/` to access the app.
5. Create new flashcards, organize them with tags, and test your memory with the Leitner system.

## Notes

- This flashcard app was built using the Django framework.
- This app is designed for personal use and has not been tested for large-scale deployment.
- This is only a sample implementation and can be further developed and customized to meet specific needs.
