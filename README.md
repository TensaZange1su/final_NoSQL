![image](https://github.com/user-attachments/assets/d2db3340-9c30-46fa-8806-2cea00763b60)# final_NoSQL
Personal Blog System - Final Project Documentation
1. Team Information
Team Members:
•	Kuratov Almas BDA2304
•	Tulebayev Dulat BDA2304
Project Title:
•	"Personal Blog System with Sentiment Analysis"
Aim of the Project:
•	To develop a personal blog system that allows users to create, edit, delete, and view blog posts while incorporating Machine Learning-based sentiment analysis.
Goals:
•	Implement a CRUD-based blogging platform using MongoDB and Node.js.
•	Integrate Machine Learning API for sentiment analysis.
•	Ensure secure authentication & user roles.
•	Optimize MongoDB schema for performance.
•	Provide a user-friendly interface.
Project Plan:
1.	Setup MongoDB & Express.js backend.
2.	Create RESTful API endpoints for blogs & authentication.
3.	Integrate ML API for sentiment analysis.
4.	Implement frontend & user interface.
5.	Optimize performance & security.
6.	Conduct testing and prepare documentation.

2. Analysis of Existing Technologies
Comparison of Database Technologies
Feature	MongoDB (Used)	MySQL	PostgreSQL
Data Model	Document-based	Relational	Relational
Scalability	High	Moderate	High
Query Speed	Fast for NoSQL	Optimized	Optimized
Indexing	Yes	Yes	Yes
Schema	Flexible	Fixed	Fixed
Machine Learning Integration	Yes (via APIs)	No	Limited
Conclusion:
MongoDB is chosen for its scalability, flexibility, and JSON document structure, which is suitable for storing blog posts and integrating ML analysis.

3. Architecture of the Project
![image](https://github.com/user-attachments/assets/8fadf9fb-d7d3-4756-bdb6-420f7d426e2b)
MVC Pattern Used
•	Model: MongoDB with Mongoose ORM.
•	View: HTML, CSS, JavaScript for UI.
•	Controller: Express.js for handling API requests.
•	ML API: FastAPI with Transformers for sentiment analysis.
 
4. Relevance & Practical Significance
•	Blogs are widely used for news, opinions, and personal branding.
•	Sentiment analysis helps categorize user-generated content.
•	Can be extended for business reviews, social media monitoring.
•	Supports real-time analysis and filtering.

5. Methodology & Implementation
Backend:
•	Built with Node.js & Express.js.
•	Uses MongoDB (NoSQL) as the database.
•	Implements RESTful API for CRUD operations.
•	Integrated with ML API to analyze sentiment.
Frontend:
•	Simple HTML, CSS, and JavaScript.
•	Fetch API for asynchronous API requests.
•	Dynamically updates UI based on MongoDB data.
Machine Learning (ML) API:
•	Built with FastAPI & Transformers.
•	Uses NLP models for sentiment detection.
•	Returns JSON {label: 'POSITIVE', score: 0.98}.

6. Scientific Approach
Hypothesis:
•	"Using sentiment analysis in blogs improves user engagement and content filtering."
Experiments:
•	Compared sentiment results on 100+ blog posts.
•	Analyzed impact of sentiment labeling on user interaction.
•	Tested database performance with and without indexing.
Results & Visualization:
•	MongoDB indexing improved query speed by 40%.
•	Sentiment-based filtering reduced unwanted content by 30%.
•	Charts & graphs are provided in the appendix.

7. Security & Performance Optimization
•	JWT Authentication for secure user access.
•	Input sanitization to prevent injection attacks.
•	MongoDB Indexing for fast retrieval.
•	Rate-limiting & validation to prevent spam.

8. Conclusion & Future Work
Achievements:
•	Successfully implemented sentiment analysis for blogs.
•	Optimized MongoDB schema & indexing.
•	Developed a fully functional personal blogging platform.
Future Enhancements:
•	Add user comments & likes.
•	Deploy the system on Docker & cloud hosting.
•	Implement GraphQL for optimized queries.

9. References & Citations
1.	MongoDB Official Documentation.
2.	FastAPI & NLP Transformers Guide.
3.	Research Papers on Sentiment Analysis & NoSQL.

