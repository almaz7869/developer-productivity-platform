# Forge — Developer Productivity Platform

A React developer workbench with a Spring Boot API for AI-assisted code review, debugging, explanations, test ideas, and interview practice.

## Stack
React 19 + Vite; Java 17 + Spring Boot; Spring Security/JWT; Spring Data JPA; MySQL; Spring AI; Docker Compose.

## Local setup
Copy `.env.example` to `.env`, set database and login values, and add `AI_API_KEY` for live model features. Run `docker compose up --build`, then open `http://localhost:5173`. API health: `http://localhost:8080/api/health`.

## Hosted demo
The GitHub Pages site is a frontend demo using sample inputs and browser-local history. It is not connected to the Spring API yet. Full AI requests require deploying the API and entering a private AI provider key on the backend host.
