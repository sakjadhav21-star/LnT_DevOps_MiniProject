# DevOps Learning Journey 
A collection of hands-on DevOps projects covering Linux administration, Python testing, Docker, Nginx, Kubernetes, and Terraform — built as part of a structured DevOps training program.

Linux Sysadmin Project
A Bash script that automates server health monitoring and logs the results. It checks disk usage, memory usage, and CPU load, and verifies the status of key services (ssh, cron, docker). Results are saved as timestamped log files in a logs/ directory for easy tracking over time.

 Python Testing (Day 3 / D30)
A simple Python calculator module paired with pytest unit tests — an introduction to Test-Driven Development (TDD). The project demonstrates how to write testable functions and validate them with automated tests.

Nginx Docker Demo
A minimal Docker setup that packages a custom static HTML page inside an Nginx container. Demonstrates the basics of writing a Dockerfile, building an image, and serving static content.

Flask CI Demo (SkillsTrainingAcademyJuneBatch1)
A Flask web application with a complete GitHub Actions CI/CD pipeline. The app exposes three endpoints — a home route, a health check, and a user details endpoint. The pipeline automatically runs pytest for testing, pylint for code quality, and builds and pushes a Docker image to DockerHub on every push to main.

Kubernetes Demo
A Kubernetes manifest that deploys an Nginx web server with 2 replicas and exposes it via a ClusterIP Service. The deployment includes defined CPU and memory resource requests and limits, demonstrating production-ready configuration basics.

Terraform Demo
A beginner Terraform project using the hashicorp/local provider — a first step into Infrastructure as Code (IaC). It provisions a local text file using a Terraform resource, introducing the core workflow of init, plan, and apply.


These projects were built during a structured DevOps training program (Skills Training Academy — June Batch). Each project targets a specific tool or concept in the DevOps ecosystem, progressing from Linux fundamentals to container orchestration and infrastructure automation.
