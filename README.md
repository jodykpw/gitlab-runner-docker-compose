# 🐳 GitLab Runner with Docker Compose

This repository contains a Docker Compose configuration for setting up a GitLab Runner with Docker support.

## 🛠️ Prerequisites

- Docker Engine
- Docker Compose
- GitLab

## 📚 Usage

1. 📦 Clone the repository:

    ```bash
    git clone ...
    cd gitlab-runner-docker-compose
    ```

2. ⚙️ Customize the sample service configuration:

- Copy the sample `docker-compose.yml.example` file:
  
  ```bash
  cp docker-compose.yml.example docker-compose-prod.yml
  ```
- Open the docker-compose file in a text editor.
- Modify or add new services according to your application needs.

3. 🚀  Deploy:

    ```bash
    docker-compose -f docker-compose-prod.yml up -d
    ```

## 📄 License

MIT / BSD

## 🇬🇧🇭🇰 Author Information

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Website: https://www.jodywan.com