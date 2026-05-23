# n8n AI Gmail Chat Agent

An AI-powered email automation workflow built with **n8n**, **Google Gemini**, and **Gmail**.  
This workflow allows users to send emails through a chat interface using natural language instructions.

## Overview

This project contains an n8n workflow where a user sends a chat message, an AI Agent understands the request, and the Gmail tool sends an email based on the extracted recipient, subject, and message body.

The workflow is useful for automating simple email sending tasks such as:

- Sending quick emails from chat
- Drafting structured email messages using AI
- Automating Gmail communication
- Building an AI-powered email assistant
- Experimenting with n8n AI Agent tools

## Workflow Name

`email automation by chat copy`

## Features

- Chat-based trigger
- AI Agent powered by Google Gemini
- Gmail email sending tool
- Simple memory support for short conversation context
- AI-generated email fields:
  - To
  - Subject
  - Message
- Gmail attribution disabled

## Workflow Components

### 1. Chat Trigger

Starts the workflow when a chat message is received.

Node:

```txt
When chat message received
