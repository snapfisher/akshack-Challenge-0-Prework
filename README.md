# Intro To Kubernetes & AKS Hack -- Student Version

Note that this repo contains only the Challenge 0 Prework instructions.  Version 02-Apr-2021.

## Introduction
This intro level hack will help you get hands-on experience with Docker, Kubernetes and the Azure Kubernetes Service (AKS) on Microsoft Azure. Kubernetes has quickly gone from being the shiny new kid on the block to the defacto way to deploy and orchestrate containerized applications.

This hack starts off by covering containers, what problems they solve, and why Kubernetes is needed to help orchestrate them.  You will learn all of the Kubernetes jargon (pods, services, and deployments, oh my!).  By the end, you should have a good understanding of what Kubernetes is and be familiar with how to run it on Azure.

This hack includes optional lectures in the Coach/Lectures folder that features short presentations to introduce key topics associated with each challenge. It is recommended that the host present each short presentation before attendees kick off that challenge.

## Learning Objectives
In this hack you will solve a common challenge for companies migrating to the cloud. You will take a simple multi-tiered web app, containerize it, and deploy it to an AKS cluster. Once the application is in AKS, you will learn how to tweak all the knobs and levers to scale, manage and monitor it.

1. Containerize an application
1. Deploy a Kubernetes cluster in Azure and deploy applications to it.
1. Understand key Kubernetes management areas: scalability, upgrades and rollbacks, storage, networking, package management and monitoring

## Challenges
- Challenge 0: **[Pre-requisites - Ready, Set, GO!](Student/00-prereqs.md)**
   - Prepare your workstation to work with Azure, Docker containers, and AKS
   
## Prerequisites

- Access to an Azure subscription with Owner access
   - If you don't have one, [Sign Up for Azure HERE](https://azure.microsoft.com/en-us/free/)
- See the Challenge 0 documentation for the rest of the prerequisites.  Challenge 0 should be done as prework before you arrive at the hack

## Repository Contents
- `../Student/Resources`
   - FabMedial app code and sample templates to aid with challenges

## Contributors
Mostly based on topics from [What the Hack](https://github.com/microsoft/WhatTheHack).  Modified/updated by Larry Claman and Paul Fisher.
