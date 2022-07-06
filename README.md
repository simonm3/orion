Purpose
=======

Setup docker container for Prefect2 Orion. Includes Orion, postgres and Orion_setup containers.

Usage
=====

To start orion::

    `
        cd orion
        make up
    `

To change configuration edit docker-compose.yml and .env.