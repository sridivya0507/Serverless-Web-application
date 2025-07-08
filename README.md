**Web-Based Employee Information Portal**

This is a **serverless web application** built using **AWS** services to capture and display employee details (ID, name, age). The front end is designed with **HTML, CSS, and JavaScript**, while the backend leverages **Lambda functions** integrated with **API Gateway** and **DynamoDB**.

### 🔧 Technologies Used

* **Amazon S3** – Hosts static website files (HTML, CSS, JS)
* **Amazon CloudFront** – Delivers web content globally with low latency
* **AWS Lambda** – Executes backend logic (insert/retrieve employee data)
* **Amazon API Gateway** – Connects frontend to Lambda
* **Amazon DynamoDB** – Stores employee records securely
* **AWS IAM** – Manages secure service-to-service permissions

### 💡 Features

* Add and view employee information through a clean, responsive UI
* Serverless architecture — no infrastructure management required
* Secure and scalable data handling via DynamoDB
* Global content delivery using CloudFront
* Seamless integration across all AWS components

### 📂 How It Works

1. **Frontend**: Static site hosted on S3, served globally via CloudFront.
2. **User Interaction**: Form input sends GET/POST requests through API Gateway.
3. **Lambda Functions**: Handle logic to insert or fetch employee data.
4. **Database**: DynamoDB stores and returns structured employee information.

### 📸 Sample UI

The portal includes form fields for entering employee details and a dynamic table to display all records.

### 🚀 Benefits

* Scalable, fast, and cost-efficient serverless setup
* Real-time updates with clean separation of concerns
* Secure data flow with fine-grained IAM roles

---

Let me know if you’d like to add a **live demo link**, **setup instructions**, or **screenshots** section!
