# n8n AI SQL Agent

This project converts natural language questions into PostgreSQL queries
using an AI Agent and executes them securely using n8n workflows.

## Features
- Natural language → SQL conversion
- PostgreSQL schema awareness
- Safe query execution
- Error handling for missing data

## Tech Stack
- n8n
- PostgreSQL / Supabase
- OpenAI
- SQL

## How it works
1. User asks a question
2. AI Agent generates SQL
3. SQL node executes query
4. Results returned as JSON

## How to import workflow
1. Open n8n
2. Import workflow JSON from `/workflows`
