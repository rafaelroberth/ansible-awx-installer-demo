# AWX Installation Project

This project automates the installation of AWX (formerly AWX Tower) using Ansible. It includes pre-requisites for Docker and various dependencies, followed by the installation of AWX.

## Prerequisites

- Docker
- Various dependencies (listed in `pre-req.yml`)

## Installation Process

1. Clone this repository.
2. Run `ansible-playbook setup-awx.yml`.
3. Follow the prompts to complete the AWX installation.

## Configuration

Configuration parameters are stored in `install-awx/vars/main.yml`. You can modify these values as needed for your environment.

## Contributing

Feel free to contribute to this project by submitting pull requests or issues.