FROM mcr.microsoft.com/devcontainers/python:3-3.12-bookworm

# Install postgres client tools so you can manually check data states 
RUN apt-get update && apt-get install -y postgresql-client && rm -rf /var/lib/apt/lists/*
