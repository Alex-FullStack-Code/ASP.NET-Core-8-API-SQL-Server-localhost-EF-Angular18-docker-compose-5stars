# Smart Meter Data Processing and Reporting System

## This project was developed to collect, process and report data from smart meters. Technologies such as .NET Core, Angular, RabbitMQ, PostgreSQL, and MSSQL were used in the project. Below is detailed information about the project and installation instructions.
Technologies Used

MeterService:
.NET Core Web API
Entity Framework Core
MS SQL Database

ReportService:
.NET Core Web API
Entity Framework Core
PostgreSQL Database
RabbitMQ
SignalR (Realtime Notification for Reports)
EPPlus (For Excel files)

Web UI:
Angular
Bootstrap

Other Tools Used:
Docker
xUnit
Docker Compose

Installation of the Project
Installation Using Docker

Start Services with Docker Compose: You can create and start all services in the Docker Compose file with the docker-compose up -d command.
Access Web UI: Open your browser and go to http://localhost:4200.

Manual Installation
If your computer has the relevant technologies, you can set the database and rabbitmq connection strings from appsettings and run the application.
