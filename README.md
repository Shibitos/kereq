# Kereq
Collective repository for social media platform named Kereq.

## Table of Contents
* [General Info](#general-information)
* [Modules](#modules)
* [Tech Stack](#tech-stack)
* [Current functionalities](#current-functionalities)
* [Screenshots](#screenshots)
* [Project Status](#project-status)

## General Information
Kereq is social media platform, where users can share information about them and create virtual communities.
This project's purpose is fully educational. Reasons why I chose this type of project:
- It is challenging
- It has a lot of potential feature/technologies to use
- It is fun

## Modules
- Backend - core of project. It handles almost all backend logic (except ones described in Communicator module)
- Communicator - uses microservice architecture to provide chat, notifications, user presence status and future functionalities based on websocket communication
- Frontend - visual part of project, which communicates with Backend and Communicator

## Tech Stack
Backend and communicator:
- Java 11
- Spring Boot 2.5.5
- Spring Cloud
- PostgreSQL
- MongoDB
- RabbitMQ
- Ehcache
- AspectJ

Frontend:
- Angular 13
- Bootstrap 5

## Current functionalities
- Creating an account and logging in
- Posting/commenting
- Liking/disliking posts and comments
- Posts and comments statistics (comments, likes and dislikes count)
- Profile pictures (currently upload only)
- Find-friends posters (advertise yourself to find friends, target age range and gender can be choosen)
- Friends system (invitations, friend management)
- Chat bar showing online friends
- Chat with history and unread messages notification
- Notifications (basic mechanism)

## Screenshots
![Wall](./screenshoots/wall.jpg)
![Profile](./screenshoots/profile.jpg)
![Chat](./screenshoots/chat.jpg)

## Project Status
In progress: early alpha.
