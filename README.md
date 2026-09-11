# GoRest REST API Testing Project

A professional **Manual REST API Testing Portfolio Project** built using **Postman** and **Newman** to validate the functionality of the **GoRest Public API**.

This project demonstrates practical QA documentation, organized API testing and real-world testing scenarios suitable for a **Junior SQA Engineer Portfolio**.

---

## Project Overview

The project focuses on validating REST API functionality through manual testing.

The testing includes:

* Authentication
* CRUD Operations
* User APIs
* Negative Testing
* Response Validation
* Environment Variable Chaining
* Newman HTML Reporting

---

## Tools Used

| **Tool**          | **Purpose**              |
| ----------------- | ------------------------ |
| Postman           | API Testing              |
| Newman            | Collection Execution     |
| GoRest Public API | REST API                 |
| Excel             | Test Cases & Bug Reports |
| Microsoft Word    | Test Plan                |
| GitHub            | Portfolio Hosting        |

---

## Modules Covered

### Authentication

* Bearer Token Authentication
* Token Validation
* Unauthorized Access Testing

### User CRUD Operations

* Create User
* Get Single User
* Get All Users
* Update User (PATCH)
* Verify PATCH Update
* Replace User (PUT)
* Verify PUT Update
* Delete User
* Verify Deleted User

### Negative Testing

* Invalid Token
* Invalid User ID
* Create Without Email
* Duplicate Email
* Invalid Gender
* Empty Name
* Missing Status
* Wrong Endpoint
* Wrong Method

---

## Test Deliverables

### Postman Collection

Contains all API requests and test scripts.

### Environment File

Contains reusable variables including:

* `base_url`
* `token`
* `userid_env`
* `name_env`
* `email_env`

### Manual Test Cases

**52 professionally documented test cases** covering positive and negative scenarios.

### Bug Report

**12 Jira-style bug reports** with severity, priority and detailed reproduction steps.

### Test Plan

IEEE-style professional test plan.

### Newman Report

HTML execution report generated using Newman.

---

## Project Structure

```text
GoRest-API-Testing-Project/
│
├── Postman/
│   ├── GoRest API Test.postman_collection.json
│   └── GoRest API Test.postman_environment.json
│
├── Documentation/
│   ├── GoRest_API_Test_Plan_IEEE.pdf
│
├── Test_Cases/
│   └── GoRest_API_Test_Cases_Professional_Portfolio.xlsx
│
├── Bug_Reports/
│   └── GoRest_API_Bug_Report_Professional_Final.xlsx
│
├── Newman_Report/
│   └── GoRest-API-Test-Report.html
│
├── Screenshots/
│
└── README.md
```

---

## Testing Workflow

1. Import the Postman Collection.
2. Import the Environment.
3. Configure the Bearer Token.
4. Execute the Create User request.
5. Store environment variables automatically.
6. Execute all CRUD requests.
7. Verify PATCH and PUT updates.
8. Execute Negative Testing scenarios.
9. Validate responses and status codes.
10. Generate the Newman HTML Report.
11. Prepare QA documentation.

---

## Newman Execution

Run the collection using Newman.

```bash
newman run "Postman/GoRest API Test.postman_collection.json" \
-e "Postman/GoRest API Test.postman_environment.json" \
-r htmlextra \
--reporter-htmlextra-export "Newman_Report/GoRest-API-Test-Report.html"
```

The generated HTML report includes:

* Request Summary
* Passed & Failed Assertions
* Response Details
* Status Codes
* Request Execution Results

---

## Validation Covered

The collection validates:

* Status Codes
* Content-Type
* Required Fields
* Environment Variables
* CRUD Verification
* Error Responses

---

## Key Skills Demonstrated

* Manual API Testing
* REST API Validation
* Bearer Token Authentication
* CRUD Testing
* Negative Testing
* Environment Variable Chaining
* Postman Test Scripts
* Test Case Design
* Bug Reporting
* Newman Report Generation
* QA Documentation

---

## Future Improvements

* Data Driven Testing
* Newman Automation
* GitHub Actions Integration
* API Schema Validation
* Automated API Testing

---

## Author

**Mahbub Sourov**

Aspiring **Junior SQA Engineer** focused on Manual Testing, API Testing and QA Documentation.

---

## License

This project is shared for educational and portfolio purposes.
