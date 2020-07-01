# opengrok
Have your local source code search engine setup in minutes!


- as option 1: you can put your projects and repositories in a folder called "repos" at your home directory `~/repos`
- as option 2: you can change the mapping in the `docker-compose.yml` and change `- ~/repos/:/opengrok/src/` to map to the location of your local repositories.
- run `docker-compose up -d`
