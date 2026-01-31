# Plugin--wordpress
Devloped &amp; Created team-showcase plugin


# Team Showcase Plugin

## Setup
1. Upload and activate the `team-showcase` plugin.
2. Add Team Members via WP Admin → Team Members.
3. Use shortcode: [team_showcase]

## Filtering
Example:
`/team/?role=designer`

## REST API Endpoints
- `/wp-json/2creative/v1/team-members`
- `/wp-json/2creative/v1/team-members/123`

## Assumptions
- Uses featured image as photo
- Short bio stored as post meta
