# ResumeForge AI

A modern, AI-powered resume evaluator that lets users upload their resumes and receive actionable feedback and ratings instantly.

## Demo
Access the live demo here: [ResumeForge AI](https://resume-forge-ai-wcll.vercel.app/)  
The platform presents a simple interface inviting users to **upload their first resume** to receive insights and ratings.

---

## Features
- **Upload Your Resume** – Easily upload your document to start the evaluation.
- **Real-Time Feedback** – Receive instant feedback on your resume’s content, structure, and alignment with industry standards.
- **ATS Score** – Get an Applicant Tracking System–style score to improve your chances with recruiters.
- **User-Friendly Interface** – Streamlined design focused on UX and clarity.

---

## Tech Stack

### **Frontend**
- **React 18** – Core UI library for building a dynamic, component-driven interface.  
- **React Router** – Client-side routing for smooth navigation.  
- **TypeScript** – Type-safe JavaScript for better maintainability and scalability.  
- **Tailwind CSS** – Utility-first CSS framework for rapid, responsive styling.  
- **Zustand** – Lightweight state management for predictable data flow.  

### **Backend / API**
- **Vercel Serverless Functions** – Handles API calls and resume analysis processing.  
- **AI Integration** – Powered by AI models for ATS scoring and resume optimization (claude-sonnet-3.7).  

### **File Processing**
- **pdfjs-dist** – PDF parsing for extracting resume content.  
- **Custom Parsing Logic** – Processes text for content, structure, and skill analysis.  

### **Build & Tooling**
- **Vite** – Fast development server and optimized production builds.  
- **ESLint & Prettier** – Code linting and formatting to maintain code quality.  

### **Deployment**
- **Vercel** – CI/CD, serverless hosting, and global CDN for lightning-fast performance.  

---

## Getting Started

### Prerequisites
- Node.js (version 18 or higher)
- npm or yarn

### Installation
```bash
git clone https://github.com/your-username/ResumeForge-AI.git
cd ResumeForge-AI
npm install  # or yarn install
