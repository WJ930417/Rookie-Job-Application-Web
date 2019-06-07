# Rookie-Job-Application-Web
The project is to create a job application website called Rookie. Rookie is an internship listing website​ that provides latest internship job postings categorized by area, requirements or other attributes for the computer science major students who are unhappy with the lack of specific targeting of Indeed and Glassdoor.

This project build a job application website called Rookie based on the database management techniques, including drawing UML Diagram, designing and build database using mySQL, creating XSLT templates and ETL workflows that combine and/or transform the external data
sources.

Finally, the project used JAVA to build JDBC data access layer and use JSP to build the web application.

The project finally delivers a website which requires a user to register and login to the account. Users have a username and password. Furthermore, we will provide service for students and companies log in to our website. Students can register, build their profiles, upload their existing resumes, and look for internship postings matching their skill sets. Using a database of internship listing website, companies can register, post jobs, and search job seeker profiles. Companies can view profiles of registered students and contact them, initiative an interview, or perform some other action related to their post. In addition, registered users should be able to search for jobs and filter the results based on location, required skills, salary, experience level, etc.

Future plans:
● As the number of users on our website increases, it is impossible to run our entire database on a single server. We could build distributed database system or MySQL cluster to reduce the pressure of data storage on one machine, and avoid single point failure or security issues.
● While the number of users on our job searching website increases, the input/output requests will increase and have a high requirement for data reading speed. Therefore, we can add cache which is a in memory database with optional durability to save database reading time. To further optimize, we could add LRU cache to remove the least recently viewed job postings in the cache to save storage space. This could be implemented using LinkedHashMap.
● It is convenient to set up our servers using Amazon EC2 for hosting the website that provides grow and shrink resources. We could choose multiple types of instance with the selection of different configurations. To ensure elastic web-scale computing, EC2 could increase or decrease our capacity within seconds.
● Also, in order to reduce the server pressure of a higher QPS, we could add a load balancer which could evenly allocate requests to several backend servers and act as a proxy to hide original servers from attacks.
