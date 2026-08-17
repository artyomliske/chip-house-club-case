# Chip House Club

> **PROFILE → RANKING → ACHIEVEMENTS → TOURNAMENT REGISTRATION**  
> A player-facing PWA built on the same data foundation as the club CRM.

[Русская версия](README.ru.md)

![TypeScript](https://img.shields.io/badge/TypeScript-0D1214?style=flat&logo=typescript&logoColor=58A79C)
![React](https://img.shields.io/badge/React-0D1214?style=flat&logo=react&logoColor=58A79C)
![Vite](https://img.shields.io/badge/Vite-0D1214?style=flat&logo=vite&logoColor=E4A244)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0D1214?style=flat&logo=tailwindcss&logoColor=58A79C)
![PWA](https://img.shields.io/badge/PWA-0D1214?style=flat&logo=pwa&logoColor=E4A244)

![Player app home screen](assets/club-home.jpg)

## Context

Players regularly asked administrators about their ranking, tournament schedule, achievements, and registration status. The goal was to move these self-service flows into a dedicated mobile-friendly app without creating a separate, inconsistent data source.

## What I built

| Area | Solution |
|---|---|
| Player profile | Personal information, history, and current status |
| Ranking | Place, points, and season-wide comparison |
| Achievements | Trophies, badges, and player progress |
| Tournaments | Schedule and pre-event registration flows |
| Mobile access | An installable PWA that works without an app-store release |

![Player ranking screen](assets/club-standings.jpg)

## Engineering decisions

The application uses the CRM’s shared data foundation while presenting a separate experience for the player. Client-side routing, request caching, and a responsive PWA shell keep frequently requested information accessible from a phone.

## Stack

`TypeScript` · `React` · `Vite` · `Tailwind CSS` · `React Router` · `TanStack Query` · `PWA`

## What is public

This repository is a public engineering case study. It intentionally excludes source code, player profiles, live tournament data, server configuration, and credentials. Screenshots use demonstration data.

[View the full portfolio case →](https://artyomliske.github.io/?lang=en#case-chclub)
