# Azure-Security-and-Monitoring

**Table of Contents**
- [Containerize the Application](#containerize-the-application)
  - [Backend](#backend)
    - [Backend Container](#backend-container)
  - [Frontend](#frontend)
    - [Frontend Container](#frontend-container)
  - [Azure Dashboard](#azure-dashboard)
  - [Backend Dashboard](#backend-dashboard)
  - [Full Dashboard](#full-dashboard)

### Containerize the application 

### Backend

```
git clone https://github.com/UnpredictablePrashant/ResumeAI backend
```

Generate a .env file including the specified fields.
```
JWT_SECRET_KEY="MYREALLYSECRETKEY"
MONGO_URL="mongodb://MONGO_URL"
OPENAI_KEY="OPENAI_API_KEY"
GMAIL_USER="THIS EMAIL IS USED TO SEND RESUMES"
GMAIL_PASS="PASSWORD USED BY NODEMAILER"
FRONT_END="URL FOR FRONTEND"
```

Execute the command below to containerize the backend of the application.

```
docker build -t backend .
```
![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/64961305-f776-44ff-931f-07cf46d055ea)
![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/b3325426-58a2-44c6-a03f-f13644fcce50)

#### Backend container 

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/aac10b78-03fb-4fae-9acc-8f32f8894ea2)


### Frontend

```
git clone https://github.com/UnpredictablePrashant/ResumeAI frontend
```

Employ the provided command to containerize the frontend segment of the application.

```
docker build -t frontend .
```

frontend container 

![Screenshot 2024-03-22 161044](https://github.com/sayanalokesh/Azure-Security-and-Monitoring/assets/105637305/0569b8a3-2979-4e5e-9320-c948006bb966)


### Azure Dashboard

Navigate to the Azure Dashboard via Home > Dashboard.

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/a3660c3d-5d4f-425b-946e-bcb67b3d38c7)

Integrate a Metric Chart tile into the dashboard.

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/8b39a879-3df1-424f-97f9-c1913ad5ea9c)

Customize the metric according to requirements.

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/282891f4-ded3-445e-a985-3f4a79069b82)


![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/e5866a90-b089-4ced-8169-9c49f803bce2)

Incorporate other tiles like memory utilization and disk utilization using a similar method.

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/d914ea5c-263f-4f4d-9e37-c8f46be89c71)



### Backend Dashboard
![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/c68df075-fe45-4492-bcf9-727ada13027e)



## Full Dashboard
Explore the comprehensive backend dashboard.

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/a27a265c-1545-4f4a-b5ab-d1b6aa4f31ff)
