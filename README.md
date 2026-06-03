# SousChef AI

An AI-powered personal sous chef that plans meals, manages groceries, and helps decide when to cook versus order food.

## Overview

SousChef AI uses long-term memory, meal planning, and Swiggy integrations to create personalized weekly food plans. The agent considers pantry inventory, dietary preferences, historical orders, recipe history, and budget constraints to generate grocery carts and food recommendations.

## Features

* Weekly meal planning
* Pantry-aware recipe suggestions
* Grocery list and cart generation
* Weekly budget management
* Recipe diversity tracking
* Food delivery recommendations
* Long-term memory for preferences and order history

## Example

**User:**

> Plan meals for next week with a ₹3,000 budget, avoid recipes from last week, and limit food delivery to two meals.

**Agent:**

* Creates a weekly meal plan
* Optimizes grocery purchases
* Generates an Instamart cart
* Suggests suitable food orders when needed

## Architecture

```text
User
  │
  ▼
SousChef AI Agent
  │
  ├── Memory Layer
  │     ├── Pantry Inventory
  │     ├── Meal History
  │     ├── Preferences
  │     └── Budget Tracking
  │
  └── Tool Layer
        ├── Swiggy Instamart
        └── Swiggy Food
```

## Tech Stack

* Python
* Docker
* Open-source LLMs (Ollama/OpenAI-compatible)
* MCP (Model Context Protocol)
* FastAPI
* SQLite/PostgreSQL
* LangGraph or PydanticAI

## Roadmap

* [ ] Core meal-planning agent
* [ ] Pantry and memory management
* [ ] Budget-aware planning
* [ ] Swiggy MCP integration
* [ ] Autonomous weekly planning
