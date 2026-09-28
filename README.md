# Recover-Mid

A lightweight Go HTTP example for demonstrating panic recovery and debug-friendly error reporting.

## Overview

This project shows how to intercept unexpected panics in a web application and handle them in a controlled way. It is designed to help illustrate the difference between a normal runtime failure and a recoverable server response.

## Basic functionality

- Recovers from panics raised during request handling
- Returns a safe error response in non-debug mode
- Shows panic details and stack traces in debug mode
- Provides sample routes that intentionally trigger panic scenarios
- Includes a simple source-view page for inspecting the relevant code location
- Preserves normal response behavior while allowing the app to recover cleanly

## Intended use

This is a small demonstration app for learning and testing panic recovery patterns in Go web handlers. It can be useful for reviewing how an application responds when unexpected errors occur during request processing.
