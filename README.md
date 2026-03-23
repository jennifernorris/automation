# automation
This is a place to keep my n8n workflows that I'm building.

## I'm learning
I've just started learning n8n, so these may seem simple at first. But as I discover new things I want to do, I'm hoping they get more interesting.

## What's here
Projects will be organized by category.

### Astrophysics
#### Near Earth Asteroid
Sends a daily email if there are any potentially hazardous near-Earth asteroids. Uses Haiku to write a description based on data available from NASA.
Credentials needed to configure and use as written:
* NASA API token (https://api.nasa.gov/)
* Anthropic API token
* Gmail OAuth
Other dependencies:
This workflow as written depends on a simple data table called Contact that stores email addresses. At a minimum it needs three fields: firstName (text), email (text), and NearEarthAsteroid (Boolean).