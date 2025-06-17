# Melvin J Bonner - AWS Solutions Architect Portfolio

Welcome to my personal AWS Solutions Architect Portfolio.  
This portfolio showcases a collection of real-world AWS cloud projects that demonstrate my technical skills, architecture design, and hands-on implementation experience.

---

## 🚀 Live Portfolio

👉https://jb24000.github.io/index.html

---

## 📂 Project Structure

The portfolio consists of individual AWS projects.  
Each project includes:

- 📄 Full PDF project document  
- 🖼 Image thumbnail used for display  
- 🔗 Clickable image to open full project document


---

## 🔧 Projects Included

- **AWS Compute Three Tier Web Application**
- **Fetch Data with AWS Lambda**
- **APIs with Lambda + API Gateway**
- **Website Delivery with CloudFront**

---

## 💻 Technologies Used

- **AWS Services:** EC2, S3, Lambda, API Gateway, CloudFront, DynamoDB, IAM
- HTML5, CSS3, Git, GitHub Pages

---

## 📈 How to Add New Projects

1️⃣ Place your new PDF file into `/projects/`  
2️⃣ Place your new thumbnail image into `/images/`  
3️⃣ Copy & paste the following block into `index.html` under the `.projects-grid` section:

```html
<div class="project-card">
  <a href="projects/YOUR-PROJECT-FILE.pdf" target="_blank">
    <img src="images/YOUR-IMAGE-FILE.png" alt="Your Project Title" />
  </a>
  <h3>Your Project Title</h3>
</div>
