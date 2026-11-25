# Gemini Recipe Analyzer

A Python notebook demonstrating multimodal generative AI integration by combining a custom recipe REST API with Google's Gemini API (`gemini-1.5-pro-latest`).

## Overview

This project fetches structured recipe data (title, ingredients, instructions, and image URL) from an external backend API, downloads and encodes the meal image into Base64 format, and passes both visual and textual context to the Gemini model for multimodal analysis and content generation.

## Features

- **REST API Integration:** Fetches live recipe data and image resources via `requests`.
- **Multimodal Processing:** Encodes image assets to Base64 and combines them with text prompts in a single payload.
- **Gemini AI Integration:** Uses the `google-generativeai` SDK to analyze meal images alongside recipe metadata.

## Project Structure

- `gemini_recipe_analyzer.ipynb` — Main notebook containing API data fetching, image Base64 encoding, and Gemini prompt execution.
