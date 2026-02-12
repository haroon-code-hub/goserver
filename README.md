# goserver

A minimal Go HTTP server built as part of a Docker learning exercise.
The server runs locally and serves a simple HTML page.

---

## Requirements

- Go 1.20+

---

## Setup

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/goserver.git
cd goserver
```

Initialize Go modules (if needed):

```bash
go mod tidy
```

---

## Build

```bash
go build
```

This creates a binary named:

- `goserver` (macOS/Linux)
- `goserver.exe` (Windows)

---

## Run

### macOS/Linux

```bash
./goserver
```

### Windows

```bash
.\goserver.exe
```

---

## Server Details

The server runs on:

http://localhost:8010

---

## Endpoints

Method Path Description

---

GET / Returns a simple HTML page

---

## Example Request

```bash
curl -i http://localhost:8010
```

---

## Project Structure

    goserver/
    │── main.go
    │── go.mod
    │── README.md

---

## Notes

- Press `Ctrl + C` to stop the server.
- This project will later be containerized using Docker.
