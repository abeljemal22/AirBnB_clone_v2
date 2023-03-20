# AirBnB_clone_v2

## Description
This repository contains the initial stage of a student project to build a clone of the AirBnB website. This stage implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

## The Command Interpreter
The command interpreter provides a simple REPL (Read-Evaluate-Print-Loop) for interacting with the models in this project only. It can be used to test the functionality of the supported storage engines as well. You can find some examples of its usage

## Environment Variables
* HBNB_ENV: The running environment. It can be dev or test.
* HBNB_MYSQL_USER: The MySQL server username.
* HBNB_MYSQL_PWD: The MySQL server password.
* HBNB_MYSQL_HOST: The MySQL server hostname.
* HBNB_MYSQL_DB: The MySQL server database name.
* HBNB_TYPE_STORAGE: The type of storage used. It can be file (using FileStorage) or db (using DBStorage).
