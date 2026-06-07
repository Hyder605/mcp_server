# mcp_server

## Overview

This repository contains a simple MCP (Model Context Protocol) server implementation. It includes two Python files demonstrating basic MCP tool creation:

1. **main.py** - Simple MCP server with dice rolling and number addition tools
2. **expense_tracker.py** - MCP server for expense tracking with SQLite database

## Contents

### Files:
- **main.py**: Basic MCP server example with two tools:
  - `roll_dice(n_dice: int)`: Rolls specified number of 6-sided dice
  - `add_numbers(a: float, b: float)`: Adds two numbers
- **expense_tracker.py**: Expense tracking MCP server with SQLite database
- **categories.json**: JSON file defining expense categories
- **expenses.db**: SQLite database file for expense storage
- **pyproject.toml**: Python project configuration
- **uv.lock**: Dependency lock file

## Features

### main.py Tools:
1. `roll_dice`: Simple dice rolling utility
2. `add_numbers`: Basic arithmetic tool

### expense_tracker.py Tools:
- Basic expense tracking functionality
- SQLite database integration
- JSON-based category definitions

## Usage

### Running the servers:

```bash
# Run the basic MCP server
python main.py

# Run the expense tracker MCP server  
python expense_tracker.py
```

### Dependencies:
- Python 3.9+
- fastmcp library
- sqlite3 (standard library)

## Note

This is a **learning/experimental** repository for exploring MCP (Model Context Protocol) server implementation. It demonstrates basic MCP tool creation and integration patterns.

## Owner

Hyder