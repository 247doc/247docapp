247docapp
============

A project related to Health care Services

a. Development Environment Setup

1. Clone the Repository

Clone the repository using either of the following methods:

	1.via SSH

 git clone git@github.com:247doc/our247docapp.git

	2.via HTTPS

git clone https://github.com:247doc/our247docapp.git

b. Setting the Environment Name in Laravel

The environment name is a string identifier that is unique for each deployment environment. The application will have different configuration values based on the environment the application is running in.

The environment name of the development machine must be set to local. We will achieve it using a server-specific config file to define the environment. To do this, create the file bootstrap/environment.php which simply returns the environment name.

<?php

return 'local';

Note: This file is omitted from the project repository, so it needs to be manually created.
