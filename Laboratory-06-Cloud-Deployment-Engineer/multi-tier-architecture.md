# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture is an application design where the system is divided into two main parts: the web/application tier and the database tier. In this mission, Nextcloud works as the web/application tier while MariaDB works as the database tier. The two containers communicate with each other to provide the complete application.

## The Web/Application Tier

The web/application tier is responsible for providing the application that users interact with through a web browser. It handles HTTP requests, displays the user interface, and processes the actions made by users. In this mission, the Nextcloud container serves as the web/application tier.

## The Database Tier

The database tier is responsible for storing and managing persistent information used by the application. This can include user accounts, credentials, and other application data. In this mission, MariaDB is used as the database container for Nextcloud.

## Why Separate Them?

Separating the web/application tier and database tier into different containers makes the system easier to manage and maintain. Each container can have its own role, resources, and configuration, which also makes it easier to update or scale parts of the application without changing the entire system.
