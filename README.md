# 🌟 NovaHR: AI-Powered HR Insights Assistant

**NovaHR** is an advanced **AI-driven HR analytics platform** designed to transform raw employee data into actionable insights. By integrating **Snowflake** for robust data storage, **AWS Bedrock (Claude)** for cutting-edge AI capabilities, and a **React-based dashboard**, NovaHR empowers HR teams to make informed, data-driven workforce decisions with efficiency and precision. 🚀

---

## ✨ Features

- **Data Upload**: Seamlessly import employee data in CSV or Excel formats for processing.
- **Interactive Dashboard**: Visualize critical HR KPIs, such as attrition rates, hiring trends, and employee performance metrics. 📊
- **AI-Powered Insights**: Leverage AWS Bedrock (Claude) to generate automated workforce summaries and actionable recommendations.
- **HR Chatbot**: Query data conversationally using natural language processing for intuitive user interaction. 💬
- **Report Generation**: Export insights to PDF or Excel formats for easy sharing and compliance. 📄
- **Secure Authentication**: Implement role-based access control using AWS Cognito or JWT for enhanced security. 🔒
- **Usage Monitoring**: Track platform usage and API costs to optimize resource management.

---

## 🏛️ System Architecture

<img width="901" height="361" alt="NovaHR_design drawio" src="https://github.com/user-attachments/assets/750307c2-4698-4bb0-b87d-a8b64151da06" />


### 🛠️ Technology Stack

| Component       | Technology                     |
|-----------------|-------------------------------|
| **Frontend**    | React, TailwindCSS (Netlify)  |
| **Backend**     | Node.js, Express (AWS Lambda) |
| **Database**    | Snowflake (Free tier support) |
| **AI**          | AWS Bedrock (Claude)          |
| **Auth**        | AWS Cognito, JWT              |
| **Hosting**     | Netlify, AWS Lambda (optional)|

### 📁 Project Structure

```
NovaHR/
├── frontend/        # React-based UI (dashboard, chatbot)
├── backend/         # Node.js API
├── design/          # Architecture diagrams, design docs
├── docs/            # Documentation
└── README.md       # Project overview
```

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (v16+), npm
- Git
- Snowflake account (free tier supported)
- AWS account (Bedrock, Cognito, Lambda)

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/NovaHR.git
cd NovaHR
```

### 2. Set Up Frontend
```bash
cd frontend
npm install
npm start
```

### 3. Set Up Backend
```bash
cd backend
npm install
npm run dev
```

### 4. Configure Environment Variables
Create a `.env` file in the `backend/` directory with the following:

```env
SNOWFLAKE_ACCOUNT=your_account
SNOWFLAKE_USER=your_user
SNOWFLAKE_PASSWORD=your_password
SNOWFLAKE_WAREHOUSE=your_warehouse
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_REGION=us-east-1
JWT_SECRET=your_jwt_secret
```

> **⚠️ Note**: Ensure `.env` files are kept secure and excluded from version control (e.g., add to `.gitignore`).

---

## 📸 Dashboard Preview
The dashboard and chatbot UI are currently under development. Placeholder paths for screenshots:
- `/screenshots/dashboard.png`
- `/screenshots/chatbot.png`

---

## 🛤️ Roadmap

- **Employee Sentiment Analysis**: Analyze text-based surveys to derive AI-driven insights on employee morale and engagement. 😊
- **Predictive Attrition Modeling**: Utilize Snowflake's machine learning capabilities to forecast employee turnover risks. 📈
- **Slack/Teams Integration**: Embed the HR chatbot into collaboration platforms for seamless access. 💬
- **Multi-Language Support**: Enable global accessibility with localized interfaces and AI responses. 🌍

---

## 🤝 Contributing
We welcome contributions to enhance NovaHR! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Please review our [Contributing Guidelines](docs/CONTRIBUTING.md) for detailed instructions.

---

## 📜 License
MIT License © 2025 Vasudev Jaiswal

---

## 📬 Contact
For questions, feedback, or support, please:
- Open an issue on [GitHub](https://github.com/VasudevJaiswal/NovaHR/issues)
- Email vasujaiswal00@gmail.com
