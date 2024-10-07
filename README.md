## E-commerce REST API in Go 
## Project Architecture:
   ![image (12)](https://github.com/user-attachments/assets/b8e82828-149e-479a-a0a5-c3d1d8a80257)
  ![image](https://github.com/user-attachments/assets/208d6a8f-e6b2-4ca2-9fbc-a498b51941f9)


### Installation

There are a few tools that you need to install to run the project.

So make sure you have the following tools installed on your machine.

- [Migrate (for DB migrations)](https://github.com/golang-migrate/migrate/tree/v4.17.0/cmd/migrate)

## Running the project

Firstly make sure you have a MySQL database running on your machine or just swap for any storage you like under `/db`.

Then create a database with the name you want *(`ecom` is the default)* and run the migrations.

```bash
make migrate-up
```

After that, you can run the project with the following command:

```bash
make run
```

## Running the tests

To run the tests, you can use the following command:

```bash
make test
```
### Get your Published API Documentation here. 
https://documenter.getpostman.com/view/21219256/2sAXxP8XYU
