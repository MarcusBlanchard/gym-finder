# Gym Finder

A Ruby on Rails app for discovering gyms, joining them, and leaving reviews. Users can browse gyms, manage their memberships from a personal dashboard, and rate the places they've trained at.

Built during the Le Wagon bootcamp.

## Features

- User accounts and authentication (Devise)
- Browse, create, and manage gyms
- Join gyms via memberships
- Leave and delete reviews
- Personal dashboard of your gyms and memberships

## Tech stack

- **Ruby** 3.1.2 / **Ruby on Rails**
- **PostgreSQL**
- **Devise** for authentication

## Getting started

```bash
bundle install
rails db:create db:migrate
rails server
```

Then open http://localhost:3000.

> Requires `config/master.key` (not committed) to decrypt Rails credentials.

## Data model

`User` · `Gym` · `Membership` · `Review`

## Deployment

The app is container-ready (see `Dockerfile`) and can be deployed to any Docker-friendly host.
