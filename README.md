# devops-intern-final
DevOps Intern Final Assessment Project

[![DevOps CI](https://github.com/zakeerhussain465/devops-intern-final/actions/workflows/ci.yml/badge.svg)](https://github.com/zakeerhussain465/devops-intern-final/actions/workflows/ci.yml)

Name: Zakeer Hussain

Date: June 2026

## Project Description

This project demonstrates a basic DevOps workflow using:

- Git & GitHub
- Linux Shell Scripting
- Docker
- GitHub Actions CI/CD
- Nomad
- Grafana Loki

## Project Structure

devops-intern-final/
│
├── hello.py
├── Dockerfile
├── README.md
│
├── scripts/
│ └── sysinfo.sh
│
├── nomad/
│ └── hello.nomad
│
├── monitoring/
│ └── loki_setup.txt
│
└── .github/
└── workflows/
└── ci.yml

## Run Python

python hello.py

## Run Linux Script

chmod +x scripts/sysinfo.sh

./scripts/sysinfo.sh

## Build Docker Image

docker build -t hello-devops .

## Run Docker Container

docker run hello-devops

## Run Nomad Job

nomad job run nomad/hello.nomad

## Monitoring

Refer to monitoring/loki_setup.txt

## Output

Hello, DevOps!
