# 🕒 Timestamp Microservice

A simple API that returns a JSON object with a Unix timestamp and UTC date. Built with Node.js and Express.

## 📦 Endpoints

- `GET /api/`  
  Returns the current time.

- `GET /api/:date`  
  Returns the Unix and UTC time for a given date string or Unix timestamp.

## 📌 Examples

- `/api/2015-12-25`  
  → `{ "unix": 1451001600000, "utc": "Fri, 25 Dec 2015 00:00:00 GMT" }`

- `/api/1451001600000`  
  → `{ "unix": 1451001600000, "utc": "Fri, 25 Dec 2015 00:00:00 GMT" }`

- `/api/invalid-date`  
  → `{ "error": "Invalid Date" }`

## 🚀 Run the project

```bash
npm install
npm start
