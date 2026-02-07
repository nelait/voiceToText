# WEB Application Development Prompt

## Application Type: Web Application
## Category: Full-Stack Development
## Template: SinglePage

---

**IMPORTANT**: This is a comprehensive development prompt for building a web application. Follow ALL guidelines, standards, and precautions outlined below for optimal code quality, security, and maintainability.

## Project Description
Convert Voice to Text and summerize bullet points. there will be only two sections 1 to take voice input buton 2nd for voice to text display.3rd for summerization of the text

## 🎯 Project Overview

**Description**: Convert Voice to Text and summerize bullet points. there will be only two sections 1 to take voice input buton 2nd for voice to text display.3rd for summerization of the text

**Key Features to Implement**:


**Development Approach**: Follow the guidelines and standards outlined in this prompt to ensure high-quality, maintainable, and secure code.

## 📋 Project Reference Documents

> **Note for AI coding tools**: Read the full documents referenced below for complete context before implementing.

### diagram_component

Below is a markdown file with a Mermaid.js flowchart TB diagram illustrating the architecture for the "VoiceToText" project. The components are organized by layer: Frontend, Backend, Data, and External, with arrows indicating the dependencies between them.

```markdown
```mermaid
flowchart TB
  subgraph Frontend
    A[Voice Input Button]
    B[Voice to Text Display]
    C[Summarization Display]
  end

  subgraph Backend
    D[Voice Processing Service]
    E[Text Summarization Service]
  end

...

📄 **Full document**: @docs/diagram_component.md

---

### Product Requirements Document (PRD)

# Product Requirements Document (PRD)

## Project: VoiceToText

### 1. Introduction

The VoiceToText project aims to develop a streamlined application that allows users to convert spoken language into written text and then generate summarized bullet points from the transcribed text. The application will feature two primary sections: one for taking voice input and another for displaying the transcribed text, along with a third section for summarizing the text into concise bullet points.

...

📄 **Full document**: @docs/prd.md

---

### Technology Stack & Architecture

# Technology Recommendations for VoiceToText Project

## 1. Frontend Technologies

### React.js
- **Justification**: React.js is a popular library for building modern web applications with dynamic user interfaces. Its component-based architecture allows for efficient UI updates and reusability. This is ideal for the interactive nature of a voice input application.

### Material-UI
...

📄 **Full document**: @docs/techstack.md

---

### Frontend Implementation Guide

# VoiceToText Frontend Implementation Guide

This guide outlines the frontend implementation for the VoiceToText project, focusing on converting voice input to text and summarizing text into bullet points.

## 1. Component Structure

The application requires the following UI components:

- **VoiceInputButton**: A button to start and stop voice recording.
- **TextDisplay**: A section to display the transcribed text.
- **SummarizedText**: A section to display the summarized bullet points.
...

📄 **Full document**: @docs/frontend.md

---

### Requirements Specification

# VoiceToText Project Requirements Document

## 1. Project Overview

The VoiceToText project aims to develop a software application that converts spoken voice input into written text and provides a summarized version of the text in bullet points. The application will consist of two main sections: one for capturing voice input and another for displaying the converted text. Additionally, there will be a functionality to summarize the displayed text into key bullet points. The project is focused on
...

📄 **Full document**: @docs/requirements.md

---

### Backend Implementation Guide

```markdown
# VoiceToText Backend Implementation Guide

**Version:** 1.0  
**Date:** 2/6/2026

---

## API Design

### Endpoints

#### 1. Voice Input Endpoint
- **Endpoint:** `/api/voice-input`
- **Method:** `POST`
- **Payload:** 
  ```json
  {
    "audioFile": "base64EncodedAudio"
  }
  ```
- **Description:** Accepts voice input in the form of a base64-encoded audio file.

#### 2. Voice to Text Endpoint
- **Endpoint:** `/api/voice-to-text`
- **Method:** `GET`
- **Parameters:** 
...

📄 **Full document**: @docs/backend.md

---

### Application Flow & User Journeys

# VoiceToText System Flow Documentation

## 1. User Workflows

### Overview
The VoiceToText application allows users to convert spoken words into text and then summarize the converted text into bullet points. The user interface consists of three main sections: a button to capture voice input, a display area for the converted text, and a section for summarizing the text.

### User Journey
1. **Voice Input**
   - User presses the "Record" button to start capturing voice input.
...

📄 **Full document**: @docs/flow.md

---

### Project Status & Progress

# Project Status Tracking Template for VoiceToText

## 1. Implementation Phases

### Phase 1: Voice Input Capture
- Develop a user interface with a button to capture voice input.
- Integrate voice capture functionality using a suitable API or library.

### Phase 2: Voice to Text Conversion
- Implement backend processing to convert captured voice to text.
- Choose and integrate a voice recognition engine or service.

### Phase 3: Text Display
...

📄 **Full document**: @docs/status.md

---

### diagram_sequence

Below is a markdown file containing Mermaid.js sequence diagrams for the key user flows specified in the requirements for the VoiceToText project. The diagrams include authentication, voice-to-text conversion, and summarization.

```markdown
# VoiceToText Project Sequence Diagrams

## 1. User Authentication Flow

```mermaid
sequenceDiagram
    actor User
    participant AuthSystem as Authentication System
    User ->> AuthSystem: Enter credentials
...

📄 **Full document**: @docs/diagram_sequence.md

---

### diagram_architecture

Certainly! Below is a markdown file with a Mermaid.js flowchart that outlines the high-level system architecture for the VoiceToText project. The architecture diagram shows the layers, technology choices, external integrations, and data storage components.

```markdown
```mermaid
flowchart TB
    subgraph User Interface
        direction TB
        A[Voice Input Button]
        B[Voice to Text Display]
        C[Summarization Display]
    end

    subgraph Frontend
        direction TB
...

📄 **Full document**: @docs/diagram_architecture.md

## 🏗️ Architecture Guidelines

**Pattern**:
- Full-stack monorepo or separate repos, API-first design approach, Shared type definitions, Microservices or monolithic architecture

**Description**:
- Application architecture pattern

**Structure**:
- **directories**: Full-stack monorepo or separate repos, API-first design approach, Shared type definitions, Microservices or monolithic architecture
- **files**: Client-server communication patterns, Database to API to frontend flow, Real-time updates (WebSockets, SSE), Caching strategies across layers
- **conventions**: File-based routing (Next.js style), API route organization, Protected routes and middleware, SEO-friendly routing

**Data Flow**:
- Client-server communication patterns, Database to API to frontend flow, Real-time updates (WebSockets, SSE), Caching strategies across layers

**State Management**:
- React State

**API Design**:
- RESTful

## 📋 Development Guidelines



## 📏 Coding Standards



## 📚 Required Libraries and Dependencies



## 🔒 Security Considerations



## ⚡ Performance Guidelines



## ✨ Best Practices

## 🧪 Testing Guidelines
  
  

## 🚀 Deployment Guidelines
  
  

## ⚠️ Critical Precautions



## 🛠️ Implementation Instructions

Build a responsive web application with modern frontend framework. Ensure cross-browser compatibility and accessibility.

### Development Workflow
1. **Setup**: Initialize project with proper structure and dependencies
2. **Core Implementation**: Build core functionality following architecture guidelines
3. **Security**: Implement security measures as outlined above
4. **Testing**: Write comprehensive tests for all components
5. **Performance**: Optimize based on performance guidelines
6. **Documentation**: Document all APIs, components, and deployment procedures
7. **Deployment**: Follow deployment guidelines for chosen platform

### Quality Checklist
- [ ] All security requirements implemented
- [ ] Performance optimizations applied
- [ ] Comprehensive test coverage achieved
- [ ] Code follows all coding standards
- [ ] Documentation is complete and accurate
- [ ] Deployment configuration is ready

---

## 📚 Final Notes

**Remember**: This prompt contains comprehensive guidelines for building a high-quality application. Prioritize security, performance, and maintainability throughout the development process.

**Code Quality**: Follow all coding standards and best practices outlined above.
**Security First**: Never compromise on security requirements.
**Performance**: Optimize early and measure continuously.
**Testing**: Maintain high test coverage and quality.

**Good luck with your development!** 🚀