## Technology used

This repository uses a number libraries to work:

- [NodeJs]
- [ExpressJs]
- [Cors]
- [Sequelize]
- [MySQL]

# Express.js Project

This is a sample Express.js project. It provides a basic setup with instructions on how to run the project and test its endpoints using Postman.

## Getting Started

Follow these steps to run and test the project:

### Prerequisites

- Node.js: Make sure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/mhk98/BlockStakReportManagementMERN.git

   ```

2. Open command prompt and type cd BlockStakReportManagementMERN
3. npm install (Install project dependencies)
4. npm run dev (Run the BlockStakReportManagementMERN project server)
5. Database: I use remote database. That's why no need to setup local mysql database environment.
6. The server will be running at http://localhost:5000
7. Available Endpoints
   POST /api/v1/user/signup: Create a new user.
   POST /api/v1/user/login: Login user.
   GET /api/v1/user/: Get a list of users.
   POST /api/v1/user/refresh-token/: Generate refresh token after expire token.
   POST /api/v1/report/create-report: Create a new report.
   GET /api/v1/report/: Get all report.
   GET /api/v1/report/:id: Get single report.
   DELETE /api/v1/report/:id: Delete a report.
   PUT /api/v1/report/:id: Delete a report.

8. JSON data for Create a new user
    ```json
{
  "Name":"Mohsin",
  "Email":"test123@gmail.com",
  "Password":"test@123",
  "Phone":"01518301096",
  "Address":"Dhaka",
  "Profession":"Engineer",
  "Favorite_colors":"Black"
}

9. JSON data for Create a new report
        ```json
{
  "Name": "Mohsin",
  "Email": "mohsinkabir2017@gmail.com",
  "Phone": "01518301038",
  "Address": "Dhaka",
  "Profession": "Engineer",
  "Favorite_colors": "Black"
}

