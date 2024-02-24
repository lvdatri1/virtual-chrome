1. Access the Firefox container:

   Open a web browser and navigate to `http://localhost:5800` to access the Firefox container.

## Managing Containers

- To stop the containers, run:

  ```bash
  docker compose down
  ```

  This command will stop and remove the containers. Use the `-v` option to also remove volumes:

  ```bash
  docker compose down -v
  ```

- To start the containers again after stopping them, run:

  ```bash
  docker compose up -d
  ```

- To view the logs of the running containers, run:

  ```bash
  docker compose logs -f
  ```

## Customizations

- You can customize the network configuration, firewall rules, and other settings by modifying the Docker Compose file (`docker-compose.yml`) and the Dockerfiles of the individual services.

## Cleanup

- If you want to remove all images and volumes associated with this Docker Compose setup, run:

  ```bash
  docker-compose down -v --rmi all
  ```

  This command will stop and remove the containers, remove volumes, and remove all images used by the containers.

## Troubleshooting

- If you encounter any issues while running Docker Compose, check the logs for error messages and consult the Docker documentation for troubleshooting tips.

```

Replace `<repository_url>` and `<repository_directory>` with the appropriate values for your repository. Update the instructions and commands as needed to match your specific setup.
```
