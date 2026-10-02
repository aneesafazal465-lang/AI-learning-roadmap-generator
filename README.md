#  AI Learning Roadmap Generator

An AI-powered application that creates a personalized learning roadmap based on the user's **field, skill level, and available learning time**.

##  Features

* Enter any learning field
* Select your skill level

  * Beginner
  * Intermediate
  * Advanced
* Enter your available learning time
* Generate a personalized AI learning roadmap
* Get topics to learn
* Get a weekly learning plan
* Get practice tasks
* Get project ideas
* Simple and easy-to-use interface

##  Technologies Used

* Python
* Streamlit
* Groq API
* Llama AI
* Google Colab
* Cloudflare Tunnel

##  How It Works

```text
User
  ↓
Streamlit Interface
  ↓
Python
  ↓
Groq API
  ↓
Llama AI
  ↓
Learning Roadmap
  ↓
Display Result
```

##  Example

The user enters:

```text
Field: Data Science
Level: Beginner
Learning Time: 3 Months
```

The AI generates a personalized roadmap such as:

```text
Month 1
- Python
- NumPy
- Pandas

Month 2
- Statistics
- Data Visualization
- Matplotlib

Month 3
- Machine Learning
- Scikit-learn
- Projects
```

##  Project Structure

```text
AI-Learning-Roadmap/
│
├── app.py
├── README.md
└── requirements.txt
```

##  Run the Project

Install the required libraries:

```bash
pip install streamlit groq
```

Run the application:

```bash
streamlit run app.py
```

##  Google Colab

This project can also be developed and run using Google Colab.

Streamlit is used for the user interface, while Cloudflare Tunnel can be used to create a temporary public URL for the application.

##  Future Improvements

* Daily learning schedule
* Learning resources
* Progress tracking
* Download roadmap as PDF
* Save previous roadmaps
* More project recommendations
* Improved user interface
* User accounts
* Database integration

##  Author

**Anisa Fazal**

This project was created as a learning project to explore **Python, Generative AI, APIs, and Streamlit application development**.

##  Project

If you find this project useful, feel free to ⭐ the repository.
