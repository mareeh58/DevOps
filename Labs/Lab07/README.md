# Lab 07: Docker Container Lifecycle Management

## Overview
This lab covers Docker installation, running and managing PostgreSQL and NGINX containers, port mapping, log monitoring, interactive shell execution, filesystem comparison (`diff`), container inspection, and creating custom images (`commit`) on an Ubuntu environment.

## Repository Structure
- **`Lab07.pdf`**: Complete lab report containing all executed commands, explanations, and embedded screenshots.
- **`screenshots/`**: Folder containing all captured verification screenshots for Tasks 1 through 5.

## Tasks Completed
1. **Task 1 — Docker Installation & Verification**: Installed Docker Engine on Ubuntu, verified service status, and ran the `hello-world` test container.
2. **Task 2 — PostgreSQL Containers**: Deployed and verified multiple PostgreSQL container versions (`postgres:9.6` and `postgres:10.10`).
3. **Task 3 — Container & Image Cleanup**: Stopped and removed `postgres:9.6` containers and deleted the unused local image.
4. **Task 4 — Multi-Port NGINX Deployment**: Ran `nginx-latest` on port `6001` and `nginx-older` (`nginx:1.30.6`) on port `6002`, verified web pages in browser, and inspected access logs.
5. **Task 5 — Container Interaction & Image Commit**: Attached/detached from the running process, created/removed files via `docker exec`, verified changes using `docker diff` and `docker inspect`, and committed the updated container as `nginx:myimage`.
