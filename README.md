# Concurrent Ticket Booking System

## Aim
To create a concurrent ticket booking system with seat locking using Redis.

## Tech Stack
- Node.js
- Express.js
- Redis

## Features
- Seat booking API
- Redis distributed locking
- Prevents race conditions
- Concurrent safe booking

## Install

1. Clone repo

git clone https://github.com/yourusername/ticket-booking-system

2. Install dependencies

npm install

3. Start Redis server

redis-server

4. Start project

node server.js

## API

Get seats

GET /seats

Book seat

POST /book/:seatId

Example

POST /book/5

## Hardware/Software Requirements

Node.js 18+
Redis
Express.js
Load testing tool (Artillery)

## Output

Seat booking response with success or failure message.
