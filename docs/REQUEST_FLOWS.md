# Request Flows

## Primary Question

> Who talks to whom?

## Purpose

This document traces who talks to whom.

## Flow: git status

Me
↓
Terminal
↓
Git
↓
Local .git folder
↓
Git reports repository state

## Flow: git push

Me
↓
Terminal
↓
Git
↓
Internet
↓
GitHub

## Flow: Flutter app talking to backend

User
↓
Flutter
↓
HTTP Request
↓
Express
↓
Route
↓
Controller
↓
Model
↓
MongoDB
↓
Response travels back to Flutter

## Version Roadmap

### Version 1 - Basic Flows
- Document common command and request flows
- Identify who receives each request
- Identify who responds

### Version 2 - Complete Conversations
- Add more detailed request journeys
- Explain intermediate components
- Visualize data movement

### Version 3 - Advanced Systems
- Trace complex workflows
- Include authentication and databases
- Explain asynchronous communication