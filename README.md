# Tampa Bay Python official website

## Generate the site locally using Docker

1. Build the container with the Python dependencies installed
  
  ```shell
  docker-compose build
  ```

2. Build the website using the docker-compose.yaml file
  
  ```shell
  docker-compose run --rm website make html
  ```
