# Phishing Detection Chrome Extension

A Chrome extension designed to detect phishing websites using a machine learning model implemented in Python and a Node.js backend. This extension checks websites in real-time and alerts the user if a site is suspected to be phishing.

## Features

- **Phishing Detection:** Utilizes a Multilayer Perceptron (MLP) algorithm to detect phishing websites.
- **Backend Integration:** A Node.js backend communicates with the machine learning model to analyze websites in real-time.
- **Machine Learning Model:** The phishing detection model is implemented in Python and integrated with Node.js for seamless operation.
- **User Alerts:** The extension alerts users about phishing websites when detected.

## Technologies Used

- **Frontend:** Chrome Extension (HTML, CSS, JavaScript)
- **Backend:** Node.js
- **Machine Learning:** Python, Scikit-Learn, MLP (Multilayer Perceptron) algorithm
- **Data Communication:** HTTP Requests between Node.js and Python

## Installation

### Prerequisites

Before starting, ensure that the following are installed:

- **Node.js**
- **Python 3.x**
- **Chrome Browser**

### Backend Setup

1. Clone the repository or download the project files.
   
2. Navigate to the **backend** directory:
   ```bash
   cd phishing-detection-extension/backend
