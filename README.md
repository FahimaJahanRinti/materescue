# 🧮 MATERESCUE

An AI-based web application that solves mathematical problems and explains solutions step by step using Artificial Intelligence.

---

## 📌 Features
- Step-by-step math problem solving
- Simple explanations for weak or average students
- Supports algebra and  calculus
- Web-based and easy to use
- AI-powered using OpenAI API

---

## 🛠️ Technologies Used
- HTML
- CSS
- PHP
- OpenAI API

---

## 🤖 AI Concepts
- Natural Language Processing (NLP)
- Generative AI
- Prompt Engineering

---

## 📂 Project Structure

---

## ⚙️ How to Run the Project

1. Install **XAMPP**
2. Copy the project folder into:
3. Start **Apache** from XAMPP Control Panel
4. Open browser and visit localhost

---

## 🔑 API Setup
1. Create an OpenAI account
2. Generate an API key
3. Replace the API key inside `index.php`

```php
$apiKey = "YOUR_API_KEY_HERE";
```
## 🚀 Implementation Details

The project is implemented in the following steps:

### Step 1: User Interface
- The frontend is built using HTML and CSS.
- A simple form allows users to enter math problems.

### Step 2: Backend Logic
- PHP handles form submission and user input.
- The backend prepares the math question for AI processing.

### Step 3: AI Processing
- OpenAI API is integrated using PHP cURL.
- A carefully designed prompt requests step-by-step solutions.
- The AI processes the math problem and generates a response.

### Step 4: Response Handling
- The API response is received in JSON format.
- PHP decodes the response and extracts the solution.

### Step 5: Result Display
- The step-by-step solution is displayed on the web page.
- Output is sanitized for security and readability.

