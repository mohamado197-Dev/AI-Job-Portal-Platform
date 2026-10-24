# AI-Powered Job Portal Platform 🚀

This project is built using a multi-application architecture. It consists of three main parts. 
You can find the source code for each part in their respective repositories below:

🔗 [Job Seeker Portal Repository](https://github.com/mohamado197-Dev/job-app)
🔗 [Admin & Company Backoffice Repository](https://github.com/mohamado197-Dev/job-backoffice)
🔗 [Shared Models Package Repository](https://github.com/mohamado197-Dev/job-shared)

AI-Powered Job Portal PlatformTech Stack: Laravel, PHP, PostgreSQL, Google Gemini AI, Docker, Tailwind CSS, Cloudinary, Spatie PDF-to-Text.

Overview: A comprehensive full-stack job recruitment platform built with a multi-application architecture. It successfully separates the public job seeker portal from the administrative company backoffice while relying on a shared Eloquent model package for data consistency.

AI Resume Parsing & Scoring (Gemini API): Integrates Google Gemini AI to extract text from uploaded PDF resumes and convert it into structured data. Upon submitting an application, the AI evaluates the candidate's qualifications against the job description, generating a precise suitability score and detailed, personalized feedback.

Advanced Authorization (RBAC & OBAC): Secured the backoffice using robust role-based access control (Admin, Company Owner, Job Seeker). Implemented ownership-based scoped access to ensure company owners can exclusively view and manage their own job vacancies and applicants.

Analytics Dashboard: Features a real-time dashboard tracking platform performance metrics, including active users, total job postings, application conversion rates, and the most applied-to jobs.

Deployment & Cloud Storage: Containerized the application using Docker with a high-performance FrankenPHP server for production deployment on Render, and integrated Cloudinary for seamless cloud-based file storage.
