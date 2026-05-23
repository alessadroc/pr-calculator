# Power Ranking Calculator

## Overview

The Power Ranking Calculator is a simple Discord Application that calculates the PR (Power Ranking) gained based on a player's placement in various  tournaments of competitive online gaming. The program allows users to use a command where they input an event, ranking, and receive a PR estimate.

An accuracy of around 95% has been achieved in PR calculation.

More on Discord Applications, in general, here: https://discord.com/blog/how-to-use-discord-apps

## Features

- User-Friendly commands
- Event-Specific PR Calculations
- Modular Design

## Instructions

1. Select an event from the dropdown menu.
2. Enter your rank for the event.
3. Click "Calculate" to see the PR gained.

## Future Plans

- More accurate calculation models beyond linear interpolation 
- Support FNCS Finals and its qualifier type events

## Tech Stack

- Python 3.x
- Matplotlib (for graphing)
- Discord.py
- dotenv to load .env

## Supported Events

- Solo Cash Cup Opens
- Solo Cash Cup Finals
- Performance Evaluation Finals
- FNCS Divisionals (1, 2, 3) - All opens.

## Run
Ensure that you have Discord installed and a server in which you have permissions to add apps. 

1. Clone or download the repository.
2. Invite the discord bot to your server using https://discord.com/oauth2/authorize?client_id=1380424855668658416
3. Use commands /calculatepr <event name> <placement> to determine results.
4. Use /events to see supported events. 