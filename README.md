Blogging Platform
This project is a full-stack blogging platform developed using Django, Docker, and AWS. It provides a platform where users can register, create, edit, delete, and view blog posts.

Features
User Registration: Users can create a new account, log in, and log out.
Blog Post Management: Registered users can create, edit, delete, and view their own blog posts.
Blog Post Viewing: All users (registered and unregistered) can view blog posts created by registered users.
Tech Stack
Backend: Django
Containerization: Docker
Deployment: AWS

Local Development
Before you begin, ensure you have Docker installed on your machine.

Clone this repository: git clone https://github.com/Yuting-Shao/BloggingPlatform.git
Navigate into the project directory: cd BloggingPlatform
Build the Docker image: docker build -t my-django-app .
Run the Docker container: docker run -it -p 8000:8000 my-django-app
The application should now be running at http://localhost:8000.

Deployment
This application is deployed on AWS using AWS Elastic Beanstalk. The database is hosted on Amazon RDS.

Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License
MIT
