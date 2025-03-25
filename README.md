# Spam-Email-Classifier
This project is a Spam Email Classifier built using HTML, CSS, and JavaScript. It is designed to classify incoming emails as either Spam or Not Spam based on the presence of specific keywords commonly associated with spam messages.

By analyzing key attributes such as the subject, sender, and content of an email, the classifier uses basic keyword detection to determine whether the email is spam. This provides an easy way to identify potentially unwanted emails without needing complex algorithms.

**Features**
1. **Email Classification**
The app allows users to input the subject, sender, and content of an email to determine if it's spam.

The classification is done by checking for common spam-related keywords in the email fields. These keywords may include terms like "win," "free," "limited offer," and more.

Users can easily classify multiple emails by entering the relevant information and getting instant results.

2. **User-friendly Interface**
The interface is simple and clean, making it easy for anyone to use. It’s built using HTML for structure and CSS for styling, offering a responsive layout.

Input fields are clearly labeled, and results are displayed immediately after submission.

The design ensures that the app is intuitive and works well across different devices.

3. **Real-time Classification**
Once an email’s details are input and the "Classify" button is clicked, the app will instantly analyze the content and display whether it is Spam or Not Spam based on the presence of pre-set spam keywords.

4. **Keyword-Based Classification Logic**
The JavaScript logic behind the classifier searches for predefined spam keywords in the subject, sender, and content of the email.

If any of these keywords are detected, the email is classified as Spam.

If no spam-related keywords are found, it is classified as Not Spam.

## Tech Stack
* **HTML:** Provides the basic structure and layout of the web page. The HTML defines the necessary input forms where users can submit email details (subject, sender, and content).

* **CSS:** The styling and visual presentation of the project. The layout is responsive, making the application user-friendly across devices. Various CSS styles help enhance the appearance of the form elements, the submit button, and the feedback area for the classification results.

* **JavaScript:** Implements the core functionality of the spam email classifier. The JavaScript code processes the input from the user, applies predefined spam rules, and provides immediate feedback regarding whether the email is classified as "Spam" or "Not Spam". The JavaScript logic can be easily expanded to include more complex classification rules.
