# Depi: AI Data Analyst Using Text-to-SQL 🐨
## Project Overview
Depi is an AI-powered Text-to-SQL system designed to simplify data analysis by enabling users to interact with databases through natural language. It bridges the gap between technical complexity and everyday data access, making SQL queries accessible to non-technical users.

## Features
Natural Language Processing (NLP): Converts plain text into SQL queries.
Optimized Query Generation: Ensures efficient and accurate data retrieval.
Dynamic Schema Handling: Adapts to changing database schemas.
User-Friendly Interface: Built using Gradio for an intuitive user experience.

## Setup Instructions
### Prerequisites
Python 3.8 or later
Gradio SDK version 5.1.0
A relational database (e.g., MySQL, PostgreSQL)

## Known Issues
### Specific Problem: Handling Dynamic Schema Changes
Description: The system may not fully adapt to large-scale or complex database schema changes.
Impact: Queries generated might fail or return incomplete results if the schema changes significantly after setup.
Proposed Solution: Enhance schema detection mechanisms to auto-update during runtime.

## Future Enhancements
Improved support for real-time schema updates.
Extended compatibility with non-relational databases.
Enhanced user interface for better accessibility.

