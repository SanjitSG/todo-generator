# Todo Generator

## Objective
The **Todo Generator** is designed as a learning tool for understanding network calls, fetching data, and rendering components in React based on dynamic data. It is designed to learn fetch a list of todos and retrieve a single todo based on user input.

## Features
- Fetch a list of todos in JSON format.
- Retrieve a specific todo by providing an ID as a query parameter.

## Hosted API Endpoints

1. **GET [https://todo-generator.onrender.com/todos](https://todo-generator.onrender.com/todos)**  
   Returns a list of todos. The number of todos returned is randomly selected, ranging from 1 to 10.

2. **GET [https://todo-generator.onrender.com/todo?id={id}](https://todo-generator.onrender.com/todo?id=1)**  
   Fetches a single todo item corresponding to the provided ID. Replace `{id}` with the actual todo ID.

## How It Works
- The `/todos` endpoint generates and returns a list of todos in JSON format.
- The `/todo?id={id}` endpoint fetches a specific todo based on the provided `id` parameter, allowing users to retrieve the relevant todo from the list.
