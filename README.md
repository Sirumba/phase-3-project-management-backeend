# projec-manager-app
Project Manager is a basic API built with ruby's Sinatra DSL. 



## Pre-Requisites
In order to use this repository you will need the following:

- Operating System **(Windows `10+`, Linux `3.8+`, or MacOS X `10.7+`)**
- RAM >= 4GB
- Free Space >= 2GB

## Built With
This application has been built with the following tools:

![ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)
![sqlite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)


- **Ruby `v2.7.+`**
- **SQlite3 `v1.6`**
- **ActiveRecord `v7.0.4`**
- **Rake `v13.0.6`**
- **Puma `v6.1`**
- **rerun `v0.14`**
- **Sinatra `v3.0.5`**

## Setup
You can setup this repository by following this manual

1. Clone the repository
    ```{shell}
   git clone https://github.com/sainamercy/task-manager-backend-sinatra.git
   ```
2. Ensure the ruby gems are setup in your machine
    ```{shell}
   bundle install
   ```
3. Perform any pending database migrations
   ```{shell}
   rake db:migrate
   ```
4. Perform any pending database seeding
   ```{shell}
   rake db:seed
   ```
4. Run the application
    ```{shell}
    rakeup
    ```
5. Open the application from your browser
    ```
   http://localhost:9292
   ```
   
## Application
This application is a simple web API that allows users to:

- Register a new account.
- Log in to existing account.
- Create PROJECT items.
- Update individual PROJECT items.
- View all PROJECT items.
- Delete a PROJECT item.

### MODELS
Database schema definitions.


## LICENSE
MIT License

# Author
This repository is maintained by:

- [Simon Sirumba](https://github.com/Sirumba)