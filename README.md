#GUVI_PROJECT1
PROJECT 1` FOR GUVI HCL
THIS PROJECT IS CREATED BY REETIRAJ GAUTAM 2312RES279 OF IIT PATNA FOR JAVA FULL STACK DEVELOPMENT.
THIS FEATURES CALCULATION OF BODY MASS INDEX AND RECOMMEND MELS ACCORDING TO NEED.

CLICK HERE   https://reetiraj123.github.io/GUVI_P1/

Technology Selection
Chose Java as the primary language for its robustness and wide acceptance in FSD projects.
Selected an IDE (e.g., IntelliJ IDEA/Eclipse) and used JDK 8+.

Project Structure & Layered Architecture
Organized the codebase into layers for clarity and maintainability:
Model: Created a UserHealthData class to store user information (height, weight, activity level) Service: Developed BMICalculator to calculate BMI and MealRecommender to advise meals based on BMI and activity.

DAO (Data Access Object): Implemented DataStorage class to manage reading/writing user data into a file.
Controller/UI: Used a Main class to handle user input/output from the console and coordinate service & DAO classes.
Input Handling and Validation
Accepted user inputs for height, weight, and activity using Java’s Scanner.
Added validation checks to ensure all entries were positive numbers and within a reasonable range.
Provided user-friendly error messages for invalid or empty inputs.
BMI Calculation & Meal Recommendation Logic

Used the standard BMI formula:
BMI=weight (kg) /(height (m sqr))
 
 Categorized BMI (underweight, normal, overweight, obese) per WHO standards.Designed the MealRecommender class to output simple, relevant diet suggestions tailored to user’s BMI and activity level.
Data Persistence
Enabled auto-creation of a data.txt file on first run via Java’s File API.Used BufferedWriter and FileWriter to append each user’s health data and recommendations.
Ensured structured file and folder organization (src/, model/, service/, etc.).Output and Error Handling
Displayed accurate BMI and meal suggestions to the user after every input.
Used try-catch blocks to handle format errors and I/O exceptions gracefully.
Ensured all errors were reported in a clear, actionable way.
Testing and Verification
Tested various scenarios and edge cases for BMI calculation and input handling.
Validated file creation and data appending worked without overwriting previous entries.Ensured output matched expectations for different user profiles
