# 🚀 JAMstack Website Deployment using AWS Amplify and Amazon S3

## 📌 Project Overview

This project demonstrates how to build and deploy a **JAMstack-based static website** using **AWS Amplify for hosting and CI/CD** and **Amazon S3 for static asset storage**.

The website is developed using **HTML, CSS, and JavaScript** and deployed automatically whenever code changes are pushed to GitHub.

The goal of this project is to understand **modern cloud-based deployment, static site hosting, and CI/CD pipelines using AWS services**.

---

# 🧰 Technologies Used

* **HTML** – Website structure
* **CSS** – Styling the website
* **JavaScript** – Adding dynamic functionality and API calls
* **Git & GitHub** – Version control and repository management
* **AWS Amplify** – Hosting and continuous deployment
* **Amazon S3** – Storage for static assets (images/logo)

---

# 🏗 Architecture

```
User
 │
 ▼
AWS Amplify (Hosting + CI/CD)
 │
 ▼
Static Website (HTML, CSS, JS)
 │
 ├── External API
 │
 └── Amazon S3 (Images / Logo)
```

---

# 📁 Project Structure

```
jamstack-aws-project
│
├── index.html
├── about.html
├── style.css
├── script.js
│
└── README.md
```

Static assets like images are stored in **Amazon S3** and accessed via public URLs.

---

# ⚙️ Project Setup

## 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/jamstack-aws-project.git
cd jamstack-aws-project
```

---

## 2️⃣ Run Website Locally

Open the `index.html` file directly in your browser.

---

# ☁️ Deployment Using AWS Amplify

### Step 1

Login to **AWS Console**

### Step 2

Navigate to:

```
AWS Amplify → New App
```

### Step 3

Select

```
Host Web App
```

### Step 4

Connect your **GitHub repository**

### Step 5

Select the branch

```
main/master
```

### Step 6

Click **Deploy**

Amplify will automatically build and deploy the application.

---

# 🪣 Amazon S3 Setup (For Images)

1. Create an **S3 bucket**
2. Upload static assets like images or logos
3. Enable **public read access**
4. Use the **Object URL** inside the HTML file

Example:

```
<img src="https://bucket-name.s3.amazonaws.com/logo.png">
```

---

# 🔄 CI/CD Workflow

Whenever changes are pushed to GitHub:

```
git add .
git commit -m "update project"
git add origin <your-Repo-url>
git push
```

AWS Amplify automatically:

1. Detects the change
2. Builds the project
3. Deploys the updated website

---

# 📸 Project Screenshots

## Website Output

<img width="1814" height="1079" alt="Screenshot 2026-03-11 213530" src="https://github.com/user-attachments/assets/b02c3d9d-a3f3-4006-9bb3-b1a749933c9e" />


---

## AWS Amplify Deployment

<img width="1919" height="1076" alt="Screenshot 2026-03-11 213523" src="https://github.com/user-attachments/assets/f117fe7d-1783-4764-8ca4-b3839ebb6db7" />


---

## Amazon S3 Bucket


<img width="1919" height="1079" alt="Screenshot 2026-03-11 213945" src="https://github.com/user-attachments/assets/5c054d95-c73b-4b43-8967-8e887ce1c04e" />

---

# 🎯 Key Features

* JAMstack architecture implementation
* Static website hosting using AWS Amplify
* CI/CD pipeline with GitHub integration
* Static asset storage using Amazon S3
* Fast global delivery using CDN

---

# 📚 Learning Outcomes

Through this project, I learned:

* How JAMstack architecture works
* How to deploy static websites using AWS Amplify
* How to integrate GitHub with AWS CI/CD pipelines
* How to use Amazon S3 for storing static assets

---

# 🚀 Future Improvements

* Add CloudFront CDN for faster global delivery
* Add a custom domain
* Implement authentication using AWS Cognito
* Convert the site into a React-based JAMstack application

---

# 👨‍💻 Author

**Sudarshan Mane**

Cloud & DevOps Enthusiast
GitHub: https://github.com/Sudarshan-Mane-2004

---
