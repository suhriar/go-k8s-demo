# go-k8s-demo

A simple demonstration project on how to containerize a Go web application and deploy it to Kubernetes.

## Overview

This repository contains:

*   A basic **Go web server** that connects to a PostgreSQL database. It reads database credentials from environment variables.
*   A multi-stage **`Dockerfile`** to build a lightweight, production-ready container image for the application.
*   Two API endpoints: `/users` to ensure a table exists and `/health` to check the database connection status.

This project serves as a practical example for a cloud-native Go application workflow, from code to a container ready for deployment.
