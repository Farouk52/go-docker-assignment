# Go Application in Docker

This repository contains a simple Go web application, containerized using Docker for the Distributed Systems course assignment.

---

## ⭐ Assignment Requirement (Docker Image)

The public image for this project is hosted on Docker Hub at the following URL:

**[https://hub.docker.com/r/farouk2003333/go-app](https://hub.docker.com/r/farouk2003333/go-app)**

---

## ▶ How to Run the Application

There are two methods to run this application.

### Method 1: Using the Pre-Built Docker Hub Image (Easiest)

This method pulls the public image and runs it directly.

1.  *Pull the image:*
    bash
    docker pull farouk2003333/go-app
    
2.  *Run the container:*
    bash
    docker run --rm -p 8080:8080 farouk2003333/go-app
    

### Method 2: Building the Image from Source

This method requires cloning the repository and building the image locally.

1.  *Clone the GitHub repository:*
    bash
    git clone [https://github.com/Farouk52/go-docker-assignment.git](https://github.com/Farouk52/go-docker-assignment.git)
    cd go-docker-assignment
    
2.  *Build the Docker image:*
    bash
    docker build -t my-local-go-app .
    
3.  *Run the locally built container:*
    bash
    docker run --rm -p 8080:8080 my-local-go-app
    

---

## 🖥 Accessing the Application

Regardless of the method used, the web server will be accessible at:
*[http://localhost:8080](http://localhost:8080)*

---

## 🧑‍💻 Submitted By

* *Name:* Farouk
* *GitHub:* [Farouk52](https://github.com/Farouk52)
* *Docker Hub Profile:* [farouk2003333](https://hub.docker.com/u/farouk2003333)
*