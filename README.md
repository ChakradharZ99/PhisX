
# PhisX - Chrome Extension for detection of Phising URLs

## Problem Statement

Phishing attacks have become increasingly sophisticated and prevalent, posing a significant threat
to individuals and organizations. Cybercriminals create fraudulent websites and URLs that appear
legitimate, tricking users into revealing sensitive information or installing malware. This project aims to develop a Chrome extension that can effectively
detect and protect users from phishing URLs in real-time, providing an additional layer of security
against these malicious attempts.


## Project

PhisX is a Chrome extension designed to detect and block phishing URLs in real-time, enhancing online security against sophisticated cyber threats.


## Solution

**Choosing a Dataset**:
   - Identify and select a comprehensive dataset containing labeled URLs, distinguishing between legitimate and phishing URLs.
   
**Training a Model**:
   - Preprocess the dataset to prepare it for training.
   - Implement and train machine learning classification algorithms to accurately distinguish between phishing and legitimate URLs.
   - Evaluate and fine-tune the model to ensure high accuracy and reliability.

**Creating an API**:
   - Develop a RESTful API using Flask to serve the trained machine learning model.
   - Ensure the API can receive URL input, process it using the ML model, and return the detection results in real-time.

**Developing the Chrome Extension**:
   - Design and implement a Chrome extension that interacts with the Flask API.
   - Ensure the extension can send URL data to the API and display alerts or block access when a phishing URL is detected.
   - Integrate user-friendly features for seamless interaction and effective real-time protection.


## Tech Stack

1. Dataset: https://archive.ics.uci.edu/dataset/327/phishing+websites

2. ML classification algorithms

3. Flask for API

4. React + TypeScript + TailwindCSS + AceternityUI - Chrome extension

## Check out this video

[![Watch this video on YouTube](https://img.youtube.com/vi/CAlDwQ-C4pI/0.jpg)](https://youtu.be/CAlDwQ-C4pI?si=s-igmY8i9POim0QD)


## Author

- [@ChakradharZ99](https://github.com/ChakradharZ99)

- Repo - https://github.com/ChakradharZ99/PhisX-Chrome-Extension

## Feedback

If you have any feedback, please reach out me at ytschakradhar@gmail.com
