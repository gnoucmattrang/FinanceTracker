# 💰 Finance Tracker App (Built with AWS)

This is a **simple finance tracking web app** built entirely on AWS using a **CI/CD pipeline with AWS Amplify**, **API Gateway**, **DynamoDB**, and **Lambda**.

![Finance Tracker (1)](https://github.com/user-attachments/assets/a70cef42-4dfd-4c85-89e1-3ca89acb49e4)

## 📊 Features
- Users can **add expenses** and **update budgets**
- Data is sent through **API Gateway** to **DynamoDB**
  - Expenses and Budgets are stored in separate tables
- A **Lambda function** (triggered via Lambda Function URL) pulls budget + expense data, analyzes it, and returns results to the frontend
- Results include:
  - Budget vs. Actual
  - Top 5 most bought items
  - Projected spending for the month
  - Alerts for overspending
- All changes to the app trigger **automatic deployments via AWS Amplify** from the GitHub repo.

## 🧰 AWS Services Used
- [x] AWS Amplify (CI/CD Deployment)
- [x] API Gateway (Routing & integration)
- [x] DynamoDB (NoSQL storage for expenses and budgets)
- [x] AWS Lambda (Data processing & analysis)
- [x] Lambda Function URL (Directly called from frontend)
- [x] CloudWatch (Optional monitoring/logging)

## 🎥 Demo Video

Watch the full app in action on YouTube:  
👉 [https://youtu.be/M0nmMp0tGOY](https://youtu.be/M0nmMp0tGOY)

## 📂 Project Structure

├── frontend/ │ └── Amplify React App (deployed from GitHub) ├── lambda/ │ └── Data retrieval and processing function ├── api-gateway/ │ └── Routes to different DynamoDB tables ├── dynamodb/ │ └── Tables: expenses, budget


You can fork this repo and deploy your own version by connecting it to **AWS Amplify**, or just study how the services were connected together.

## 🤝 Let's Connect

If you have ideas to make this better, feel free to drop a PR or open an issue!

📬 [LinkedIn](https://www.linkedin.com/in/ifeloludavid)  
📺 [Watch the Demo](https://youtu.be/M0nmMp0tGOY)

---

#AWS #Serverless #CloudApp #FinanceTracker #CI_CD #Lambda #DynamoDB #APIgateway #AWSAmplify #CloudProjects
