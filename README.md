# Hadoop Docker Compose

This repository contains a minimal example for running Hadoop inside Docker containers using Docker Compose. The setup is intended for testing or experimentation purposes rather than production use.

## Directory Structure

- `hadoop-config-setup/` – Contains the Dockerfile, `docker-compose.yml`, and a helper script used to start the container.

## Quick Start

1. Build the Docker image from within the `hadoop-config-setup` directory:
   ```bash
   docker-compose build
   ```
2. Launch the container:
   ```bash
   docker-compose up
   ```
   This exposes port `5000` from the container.

## Notes

The included `test.sh` script simply keeps the container running. You can extend the configuration to suit more advanced Hadoop setups.
