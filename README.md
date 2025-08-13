# CourseViewer

A web application for browsing and viewing online courses and their authors, built with AngularJS.

## Live Demo

See the app: https://course-viewer.netlify.app

## Overview

CourseViewer is a single-page application that provides an interface for exploring courses and authors. The application features:

- **Course Browser**: Browse available courses with detailed information
- **Author Profiles**: View author biographies and their course listings
- **Course Details**: Access course modules, descriptions, and discussions
- **User Authentication**: Login system with user status management
- **Responsive Design**: Bootstrap-powered UI for cross-device compatibility

## Tech Stack

- **Frontend**: AngularJS 1.x
- **UI Framework**: Bootstrap 3.x
- **Routing**: UI-Router for client-side navigation
- **Authentication**: Custom security module
- **HTTP Client**: jQuery for AJAX requests

## Project Structure

```
CourseViewer/
├── App/                    # Demo/example components
├── Content/               # CSS styles (Bootstrap + custom)
├── Scripts/               # JavaScript dependencies
├── course-viewer/         # Main application code
│   ├── author/           # Author-related components
│   ├── course/           # Course-related components
│   ├── app-module.js     # Main application module
│   └── *.component.js    # Shared components
└── Index.html            # Main HTML entry point
```

## Features

### Course Management
- Course listing and search
- Detailed course information
- Course modules and curriculum
- Recent courses tracking

### Author System
- Author profiles and biographies
- Author course listings
- Author navigation

### User Features
- User authentication
- Discussion system for courses
- Responsive navigation

## Getting Started

1. Clone the repository
2. Open `CourseViewer/Index.html` in a web browser
3. Or serve the files using a local web server for development

## Components Architecture

The application follows a component-based architecture with:
- Route-based components for main views
- Reusable UI components
- Service layer for API communication
- Centralized state management through services
