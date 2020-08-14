# Pequi
URL shortener using Cloud Firestore

[![Go Report Card](https://goreportcard.com/badge/github.com/noverde/pequi)](https://goreportcard.com/badge/github.com/noverde/pequi)
![Build](https://github.com/noverde/pequi/workflows/Build/badge.svg?branch=master&event=push)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## setup

```
go mod tidy
```

## run

**var envs:**
- HTTP_PORT _default: 8080_
- FIRESTORE_PROJECT
- FIRESTORE_COLLECTION

```
go run main.go
```

## Supported Databases

- [x] In Memory
- [ ] Redis (open a Pull Request)
- [x] Firestore
- [ ] DynamoDB (open a Pull Request)
- [ ] MySQL (open a Pull Request)
- [ ] Postgres (open a Pull Request)
- [ ] SQLite (open a Pull Request)