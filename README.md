# GitHub Explorer API

Welcome to the GitHub Explorer API repository!

## Description

This repository contains the source code for an intermediary API built in C# as part of the Blip technical challenge. The API integrates with the public GitHub API to retrieve information about the 5 oldest repositories from the "takenet" organization.

## Accessing the API

You can access the API online at [https://githubexplorerapi-butr.onrender.com/api/repositories](https://githubexplorerapi-butr.onrender.com/api/repositories?user=takenet&language=csharp&sort=updated-asc&include_forks=true&limit=2).

### Endpoint Details

- **Path:** `/api/repositories`
- **Parameters:**
  - `user`: GitHub username (e.g., "takenet")
  - `language`: Filter repositories by programming language (optional)
  - `sort`: Sort repositories by "updated" (default) or "created" (optional)
  - `include_forks`: Include forked repositories (true/false, default: false)
  - `limit`: Limit the number of repositories returned (optional)

## How to Use

To use the API, simply make a GET request to the specified endpoint with the desired parameters. You will receive a JSON response containing information about the repositories.

## Chatbot Flow

The chatbot flow for this project can be found in the [conversation flow document](https://bit.ly/3bxfe9F). This document outlines all interactions and messages expected from the chatbot.

