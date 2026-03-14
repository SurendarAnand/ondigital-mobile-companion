# OnDigital Mobile Companion

A Flutter mobile application that integrates with Salesforce to provide
mobile access to training videos managed inside Salesforce.

# Purpose

This project demonstrates how Salesforce OnDigital video management can be extended to mobile devices using Flutter.

# Features

- Fetch training videos from Salesforce
- Play videos in mobile
- Track video completion

# Architecture

Salesforce (Training_Video Object)
        │
        │ REST API
        ▼
Flutter Mobile App
        │
        ▼
Video Player (YouTube / Vimeo)

# Tech Stack

- Flutter
- Salesforce REST API
- OAuth Authentication
- YouTube / Vimeo video embedding
