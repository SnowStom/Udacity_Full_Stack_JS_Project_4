## Infrastructure
    The infrastructure of the application contains three parts:
        - A PostgreSQL-based relational database, hosted on AWS Relational Database Service (RDS)
        - A backend API project hosted via Amazon Elastic Beanstalk, this interacts with the database above to store and receive data
        - A frontend app hosted via Amazon Simple Storage Service (S3), interacting with the backend via APIs