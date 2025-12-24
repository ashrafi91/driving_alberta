# Alberta Driver's Knowledge Assessment Web App 🚗

A lightweight, interactive web application designed to help users prepare for the Alberta Basic Licence Driver's Knowledge Test (Class 7). This single-page application features 120 randomized questions covering road rules, safety regulations, and traffic sign identification.

**[▶️ View Live Demo](https://inspiring-kitten-4e8631.netlify.app/driver_quiz.html)**

## 📋 Features

* **Extensive Question Bank:** Includes 120 questions sourced from the official Driver's Guide and practice materials.
* **Randomized Exam:** Questions and answer options are shuffled every time the exam starts to prevent memorization of patterns.
* **Instant Feedback:**
    * Immediate visual cues (Green for Correct, Red for Incorrect) after selecting an answer.
    * Auto-advances to the next question after a short delay.
* **Flexible Session:** Users can choose to "Finish Exam Now" at any point to see their current standing.
* **Personalization:** Users can input their name, which is displayed throughout the session and on the final scorecard.
* **Comprehensive Review:**
    * Detailed breakdown of incorrect answers.
    * Displays the user's choice vs. the correct answer.
    * **Visual Review:** Includes traffic sign images in the review section for better retention.
* **Scoring System:** Calculates the final percentage and indicates a **PASS (≥85%)** or **FAIL**.

## 🚀 How to Run Locally

Since this is a static web application using vanilla JavaScript, no backend server or installation is required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ashrafi91/driving_alberta.git](https://github.com/ashrafi91/driving_alberta.git)
    ```
2.  **Navigate to the folder:**
    ```bash
    cd alberta-driver-quiz
    ```
3.  **Open the application:**
    * Simply double-click `driver_quiz.html` to open it in your default web browser.

## 📂 Project Structure

To ensure traffic sign images load correctly, the file structure should look like this:

```text
/
├── driver_quiz.html      # Main application file
├── 7.png                 # Traffic sign image
├── 11.png                # Traffic sign image
├── ...                   # (Other numbered sign images corresponding to Question IDs)
├── 115.png               # Traffic sign image
└── README.md             # Documentation