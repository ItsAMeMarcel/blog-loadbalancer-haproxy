# Basics: Loadbalancing with HAProxy 

This repository contains code examples from the blog post "". The guide demonstrates how to set up a simple load balancing environment using HAProxy and Podman.

## Prerequisites

- Podman and Podman Compose installed 
   * For Ubuntu 22.04 LTS: [Installation Guide](https://itsamemarcel.micro.blog/2024/12/19/install-podman-desktop.html).

## Project Structure

The project consists of:
- A PHP web application to display server hostnames.
- An HAProxy configuration for load balancing in round robin mode.
- A `compose.yaml` file to define and manage services with Podman Compose.

## Usage

1. Clone the repository and navigate to the project directory.
2. Start the environment with:
   ```bash
   podman-compose up
   ``` 
3. Access the load balancer at `http://localhost:8080/`.

## Key Learnings
- Containerize applications with Podman.
- Configure HAProxy for load balancing.
- Use Podman Compose to manage multi-service setups.
