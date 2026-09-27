# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A **Two-Tier Architecture** divides an application into two main parts: the **Web/Application Tier** and the **Database Tier**. Each tier has a different job, but they communicate with each other to make the whole application work. Nextcloud serves as the web/application tier, while MariaDB serves as the database tier.

## The Web/Application Tier

The Web/Application Tier is responsible for handling the part of the system that users interact with. It receives requests, processes application functions, and sends requests to the database when information needs to be stored or retrieved.

## The Database Tier

The Database Tier is responsible for storing and managing the data used by the application. It receives requests from the Web/Application Tier and provides the needed information back to the application.

## Why Separate Them?

Separating the web application and database makes the system easier to manage and organize. Each container has its own purpose and can be managed separately. Containers also provide isolated environments for applications, which helps keep different services separated. This setup makes the system easier to maintain and expand than placing the web application and database together in one container.