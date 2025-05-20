# AI Chatbot

This is a Drupal recipe for AI chatbot with OpenAI and Pinecone integration. This repository contains recipes for implementing an AI Chatbot with Drupal, OpenAI, and Pinecone.

This is an "opinionated" approach; there are many other llms and vector dbs out there to choose from.  The purpose of this recipe is to give a "quick start" solution.

## Installation

1. Set "minimum-stability": "dev" in your composer.json
1. Install the recipe: `composer require koppie/ai-chatbot-recipe`
1. Clear the cache: `drush cr`
1. Enable the recipe: `drush recipe ../recipes/ai-chatbot`
1. Configure the modules (each chatbot is unique)
1. Get API keys from OpenAI and Pinecone
