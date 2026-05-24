# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal travel planning repository for a couple (repo owner + 楠宝). Documents past trips and plans future itineraries, focusing on natural scenery and local food.

## Repository Structure

- `README.md` — Travel log: cities visited, future plans, and shared preferences
- `city/<城市名>/` — Per-city itinerary markdown files (e.g., `city/西安/0530-0531两日游.md`)
- `img/` — Reference images (food, attractions) linked from city itineraries

## Travel Preferences

- **Food**: "新鲜的碳水" — street snacks like 肉夹馍、菜煎饼 are go-to consensus picks
- **Nature**: Grand landscapes preferred, but need solid infrastructure backup (escalators, cable cars) for 楠宝's stamina

## Conventions

- City directories use Chinese city names (e.g., `西安`, `苏州`)
- Itinerary filenames include date ranges: `MMDD-MMDD<描述>.md`
- Images use relative paths from the markdown file location (e.g., `..\..\img\xxx.jpg`)
- Each itinerary covers: 住宿 → 必去景点 → 必吃美食 → 具体行程 (with time blocks)
- Checkboxes (`- [ ]`) for unvisited spots; update to `- [x]` after visiting
- Documents end with `♦`
- All content is in Chinese (Simplified)
