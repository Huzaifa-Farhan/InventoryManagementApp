# Full-Stack Inventory Management Dashboard
 Full Stack Application & Deployed on AWS. This repository provides a comprehensive solution for building and deploying a scalable inventory management dashboard.  
Access the Full-Stack Inventory Management App by clicking [HERE!](https://main.dl2vtbwbu9zvg.amplifyapp.com/)

## Features
* Inventory Tracking: Manage product data efficiently.
* Dynamic UI: Interactive dashboards for data visualization and management.
* Scalable Backend: RESTful API with Prisma and Node.js.
* Cloud Integration: Deployed on AWS for scalability and reliability.

## Tech Stack
### Frontend
* Next.js: Framework for server-rendered React apps.
* Tailwind CSS: Utility-first CSS framework for rapid UI development.
* Material UI Data Grid: For rich table displays.
* Redux Toolkit: State management.
* Redux Toolkit Query: Efficient data fetching and caching.

### Backend
* Node.js: Backend runtime.
* Prisma: ORM for database management.

### Deployment
* AWS EC2: Virtual servers for deployment.
* AWS RDS: Managed database service.
* AWS S3: Object storage for assets.
* AWS API Gateway: API management.
* AWS Amplify: Frontend hosting.

## Setup Guide

1. Clone the Repository:

```bash
git clone https://github.com/your-repo/inventory-management.git
cd inventory-management
```

2. Install Dependencies:
* Backend:
```bash
cd server
npm install
```
* Frontend:
```bash
cd client
npm install
```

3. Configure Environment:
* Update .env files in server and client with appropriate API keys, database URLs, and AWS configurations.

4. Database Setup:
* Use Prisma schema to define the database model.
* Seed the database:
```bash
npx prisma migrate dev
node prisma/seed.js
```

5. Run the Application:
* Start Backend:
```bash
cd server
npm start
```

* Start Frontend:
```bash
cd client
npm run dev
```
6. Deploy to AWS:
* Follow the AWS EC2 Setup Guide for deployment.
* [AWS commands](https://github.com/ed-roh/inventory-management/blob/master/server/aws-ec2-instructions.md)

## Resources
1. Configuration Files:
* Tailwind Configuration
* Redux Store

2. Database:
* Prisma Schema
* Seed Script
* Data Model Diagram

3. Assets:
* Download Server Assets

## Support
Tutorial Video: Watch the YouTube tutorial for step-by-step instructions. [Link Here!](https://youtu.be/ddKQ8sZo_v8?si=0idf-ncs2-GLme9l)
