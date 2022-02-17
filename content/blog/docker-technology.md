---
title: "Docker Technology"
date: 2022-02-17T09:19:29-04:00
slug: "docker-technology"
description: "This is an example post for hugo-theme-codex."
keywords: ["docker", "container", "package", "applications"]
draft: false
tags: ["docker", "container", "package", "lightweight"]
math: false
toc: true
---

## History
Docker containers were developed in Go by Docker, Inc. and launched in 2013. Soon after, many companies such as Amazon Web Services (AWS), Microsoft, IBM, and Oracle started offering Docker container services within their cloud solutions. To this day, the Docker project is open source (https://github.com/moby/moby).  

## What is a container?
In simple words, a container defines an isolated environment in which a packaged application runs. Once a Docker image, or image file, which contains all dependencies and required modules to run an application is created, then the Docker image can be run in a container. Unlike virtual machines (VMs), multiple containers can run on a single operating system, or host operating system. This allows for less computational overhead in comparison to VMs. Another advantage of Docker images is that an image can be duplicated and run on multiple containers with each image having its own isolated environment.
