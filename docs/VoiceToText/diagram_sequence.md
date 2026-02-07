Below is a markdown file containing Mermaid.js sequence diagrams for the key user flows specified in the requirements for the VoiceToText project. The diagrams include authentication, voice-to-text conversion, and summarization.

```markdown
# VoiceToText Project Sequence Diagrams

## 1. User Authentication Flow

```mermaid
sequenceDiagram
    actor User
    participant AuthSystem as Authentication System
    User ->> AuthSystem: Enter credentials
    AuthSystem ->> AuthSystem: Validate credentials
    alt Credentials valid
        AuthSystem -->> User: Authentication successful
    else Credentials invalid
        AuthSystem -->> User: Authentication failed
    end
```

## 2. Voice Input and Conversion Flow

```mermaid
sequenceDiagram
    actor User
    participant VoiceInput as Voice Input System
    participant TextConversion as Text Conversion System
    User ->> VoiceInput: Press voice input button and speak
    VoiceInput ->> TextConversion: Send voice data for conversion
    TextConversion ->> TextConversion: Convert voice to text
    TextConversion -->> VoiceInput: Return converted text
    VoiceInput -->> User: Display converted text
```

## 3. Text Summarization Flow

```mermaid
sequenceDiagram
    actor User
    participant TextConversion as Text Conversion System
    participant Summarization as Summarization Module
    User ->> TextConversion: Request text summarization
    TextConversion ->> Summarization: Send text for summarization
    Summarization ->> Summarization: Summarize text into bullet points
    Summarization -->> TextConversion: Return summarized text
    TextConversion -->> User: Display summarized bullet points
```
```

These diagrams illustrate the key interactions between the user, the system's components, and the data flow for the VoiceToText application's main features.