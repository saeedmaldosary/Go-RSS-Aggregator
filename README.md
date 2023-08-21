# Go-RSS-Aggregator

A Go-based application for aggregating RSS feeds.

## Overview

This application provides an API to manage and aggregate RSS feeds. It allows users to create accounts, add feeds, and manage their feed subscriptions.

## Features

1. **User Management**: Users can create accounts and manage their details.
2. **Feed Management**: Users can add new RSS feeds and view the list of available feeds.
3. **Feed Subscription**: Users can subscribe to specific feeds and manage their subscriptions.

## Setup

1. **Environment Variables**: Ensure you have the `.env` file set up with the necessary environment variables:
   - `PORT`: The port on which the server will run.
   - `DB_URL`: The connection string for the PostgreSQL database.

2. **Database**: The application uses PostgreSQL. Ensure you have it installed and set up.

3. **Dependencies**: The application uses various Go packages. Ensure you have them installed.

## API Endpoints

- `/healthz`: Health check endpoint.
- `/err`: Error handler endpoint.
- `/users`: Endpoint for user creation and retrieval.
- `/feeds`: Endpoint for feed creation and retrieval.
- `/feed_follows`: Endpoint for managing feed subscriptions.
