# [Cyber Abuse Recognition System Using BERT](Cyber-Abuse-Recognition-System-Using-BERT)

[![GitHub license](https://img.shields.io/github/license/mounika1606/Cyber-Abuse-Recognition-System-Using-BERT)](LICENSE)  [![GitHub issues](https://img.shields.io/github/issues/mounika1606/Cyber-Abuse-Recognition-System-Using-BERT)]()  [![GitHub contributors](https://img.shields.io/github/contributors/mounika1606/Cyber-Abuse-Recognition-System-Using-BERT)]()  [![GitHub last-commit](https://img.shields.io/github/last-commit/mounika1606/Cyber-Abuse-Recognition-System-Using-BERT)]()

Detect and prevent cyber abuse with the power of deep learning. The **Cyber Abuse Recognition System Using BERT** uses the BERT model to identify harmful content in online communications and provide real-time moderation support.

---

## Table of Contents

- [About](#about)  
- [Limitations & Future Work](#limitations--future-work)  
- [Features](#features)  
- [Requirements](#requirements)  
- [Setup and Installation](#setup-and-installation)  
- [Usage](#usage)   
- [Screenshots](#screenshots)  
- [License](#license)  


---

## About

**Cyber abuse** includes harassment, trolling, impersonation, and other harmful behavior online. This project presents a detection system leveraging **BERT (Bidirectional Encoder Representations from Transformers)** to understand and classify text. It outperforms traditional models like Logistic Regression with higher accuracy and better contextual understanding.

- **Dataset**: Jigsaw Toxic Comment dataset  
- **Accuracy**: Improved from **93.5% (Logistic Regression)** to **96.5% (BERT)**  
- **Interface**: Web-based using **Flask (backend)**, **React (frontend)**, and **MySQL (database)**

---

## Limitations & Future Work

## Limitations

- Struggles with false positives/negatives  
- Heavy dependence on labeled data  
- Not real-time yet  
- Slower on large datasets with limited hardware

## Future Work

- Real-time detection  
- Integration with browser extensions  
- Enhanced UI/UX  
- Cross-platform deployment  
- Continuous learning from feedback  
- Integration with social media platforms  
- Stronger security & privacy protection

---

## Features

-  BERT-based deep learning model for text classification  
-  Preprocessing pipeline (lowercase, punctuation removal, stopwords)  
-  Flask backend with REST API  
-  React frontend  
-  MySQL database support  
-  Accuracy improvement from 93.5% to 96.5%

---

## Requirements

## Hardware

- CPU: Intel i3 or better  
- RAM: 8 GB or more  
- Storage: 500 GB or more  

## Software

- **Frontend**: React JS  
- **Backend**: Python 3.11  
- **Web Framework**: Flask  
- **Database**: MySQL  

## Python Libraries

```bash
transformers
pandas
scikit-learn
nltk
flask
flask_sqlalchemy
python-dotenv
```
## Setup and Installation
1. Clone the Repository
  ```
git clone https://github.com/gundlasreeja/Cyber-Abuse-Recognition-System-Using-BERT.git
cd Cyber-Abuse-Recognition-System-Using-BERT
```
2. Install Backend Requirements
```
pip install -r requirements.txt
```
3. Set Up Environment Variables
```
FLASK_APP=wsgi.py
FLASK_ENV=development
```
4. Run Flask Application
```
python wsgi.py
```
5. Run Frontend (if using React)
```
cd frontend
npm install
npm start
```
## Usage
Navigate to the web application.
Enter a sentence or comment into the input field.
Submit the text.
The system returns whether the input is abusive or not.

## Screenshots

**Login Page**

![Image](https://github.com/user-attachments/assets/bc177eed-c9fc-4049-8d6b-696c5b9e71cd)

**Register Page**

![Image](https://github.com/user-attachments/assets/902f9ebe-7e18-4025-8e04-36bdd2642c16)

**Message Page1**

![Image](https://github.com/user-attachments/assets/66ec9918-2925-4892-bb2b-0943952e38f1)


**Result Page1**
![Image](https://github.com/user-attachments/assets/28af8d88-6893-4296-9ff0-4eae4fba8ea4)

**Message Page2**

![Image](https://github.com/user-attachments/assets/412e34e1-a541-48ce-829f-cac5c553e797)

**Result Page2**

![Image](https://github.com/user-attachments/assets/c7c42717-1c4d-46fe-a319-89bd1cc4f289)

## License

This project is licensed under the [Apache License 2.0](LICENSE) - see the [LICENSE](LICENSE) file for details.
