# Greencard Accelerator

### Overview ###

This document provides straightforward, step-by-step plans to fast-track your U.S. Green Card application. Follow the specific checklist and strategies for your application type.

### Running in dev mode ###

The 'gacc' bash script (located in the root of the greencard_accelerator project) contains a collection of convenience commands to make it easy to work within the project. Change your working directory to the root of the greencard accelerator project before using the script:

    $ cd /path/to/greencard_accelerator

Start up the app:

    $ ./gacc start

Then navigate to http://localhost:8081/

To tail app logs, run the following:

    $ ./gacc logs

To stop the app, run the following:

    $ ./gacc stop

USE WITH CAUTION! If you want to completely clean your local docker environment (e.g. you made tons of local docker / docker compose changes and need wipe all containers, volumes, networks and start clean) run the following command (This will clean your full docker environment and not just docker assets associated with this project):

    $ ./gacc destructive_clean