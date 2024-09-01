## Library Management System - Incubyte Assesment
Test coverage is 100% hence that serves as a documentation

![image](https://github.com/user-attachments/assets/ae595ba3-c978-4fbd-91b8-7deac9fb507e)

## Introduction
This project is a Library Management System designed as part of the Incubyte assessment test. The system allows you to manage books, users, borrowing, and returning processes efficiently.

## Features
1. Add Books: Seamlessly add new books to the library.[book, user validation, register user if not registred previously]
2.	Borrow Books: Allow users to borrow books while maintaining proper records.[restrict max book borrowing to two, restrict single copy for single user]
3. Return Books: Track the return of borrowed books.[verify user, book combination]
4. User Management: Manage library users effectively.[register users]

## Setup & Installation
### ----- Clone the Repo -----
### For Cloning
```bash
git clone https://github.com/Dhanvi03/incubyte.git
```

## Running the Tests

### Prerequisites
Before you run the test cases, make sure you have the following installed:
- [**Apache Maven**: For building the project and managing dependencies.](https://dlcdn.apache.org/maven/maven-3/3.9.9/binaries/apache-maven-3.9.9-bin.zip)
- Add the bin directory of Maven to your system’s PATH environment variable.

**Build the Project and Run Tests**:
   ```bash
   mvn test
   ```
   This command compiles the project and runs all the tests.
