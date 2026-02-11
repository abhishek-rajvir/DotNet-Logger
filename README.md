# DotNet-Logger

A lightweight logging application built with **ASP.NET MVC** that provides logging functionality through a REST API endpoint.

---

## Overview

**DotNet-Logger** is a centralized logging service that allows applications to send log messages via HTTP requests.  
It can be integrated with other services or applications to collect, store, and manage logs in a structured and consistent format.

The system is designed to be simple, extensible, and easy to integrate into distributed or microservice-based architectures.

---

## Features

- REST API endpoint for logging
- Supports multiple log levels (Info, Warning, Error, Debug, Critical)
- Structured log storage
- Clean and extensible architecture
- Easy integration with external systems
- JSON-based request/response handling

---

## Tech Stack

- ASP.NET Core 
- C#

---

## How It Works

1. External applications send log data via HTTP POST request.
2. The API validates and processes the request.
3. The log entry is stored (file depending on specified location).
4. A success response is returned.

---
