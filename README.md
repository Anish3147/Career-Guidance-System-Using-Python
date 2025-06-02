# Career Guidance System using ML

[![License: Creative Commons](https://img.shields.io/badge/License-CC_BY--NC_4.0-blue.svg)](https://creativecommons.org/licenses/by-nc/4.0/deed.en)

## Description

Career Guidance System using ML is a machine learning-powered career recommendation system for matriculates. The system recommends whether students should opt for Science, Arts, or Commerce stream based on their interests and academic performance.

The system workflow involves:
1. Student signup and input of interests and academic performance.
2. Completion of a computer adaptive test comprising 60% interest-related questions and 40% other questions.
3. Filling out an interest survey form.
4. Display of scores and prediction of the recommended stream by the ML model.

The computer adaptive quiz question dataset is curated by compiling questions sourced from the internet and refining them to suit our needs. Additionally, a portion of the training dataset for the ML model is gathered through student surveys,ensuring the dataset's accuracy and relevance.

## Tech Stack

- **Backend:** Python Flask
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript
- **IDE:** Spyder
- **Python:** 3.11.4
- **Flask:** 2.3.2
- **Werkzeug:** 2.3.6
- **Scikit-learn:** 1.3.2 (used Random Forest Regressor for model training)

## Demo Video

![](/static/demo.gif)

[Download Demo Video](static/demo.mp4)

## System Flow Diagram

![System Flow Diagram](/static/System_flow.png)


## Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/Akshar-Vadwala/career-guidance-system.git
    ```

2. Install the required dependencies.

3. Set up the MySQL database by creating a database named `careerguidance` and importing the schema from `/DATABASE SCHEMA.txt`.

4. Run the Flask application:

    ```bash
    python app.py
    ```

5. Access the application in your web browser at `http://localhost:5000`.

## Contribution

Contributions to this project are welcome! Here's how you can help:

- Use the project for testing and provide feedback on its functionality and user experience.
- Enhance the training dataset by participating in quizzes and supplementing the question dataset with additional questions or refining existing ones.
- Report any bugs or issues you encounter while using the application.
- Enhance the codebase by fixing bugs, optimizing performance, or adding new features.

Please note that commercial use of the code or any derived work is not allowed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/deed.en). Contributions should align with the non-commercial nature of the project.

Feel free to fork the repository, make your changes, and submit a pull request. Your contributions are appreciated!

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/deed.en). See the [LICENSE](LICENSE) file for details.

