# Plat Map

Creates interactive property plot maps for the Estatik Real Estate plugin. Allows admins to upload a map image, define property coordinates, and render clickable plots on the frontend via a shortcode.

## Features

- Custom post type `plat_map` for managing maps
- Admin metabox to upload a map image and set property coordinates
- `[plat_map id="X"]` shortcode to display the map on any page
- Requires Estatik + ACF

## Usage

1. Upload the `plat-map/` folder to `/wp-content/plugins/` and activate.
2. Go to **Plat Maps** in the WordPress admin and create a new map.
3. Upload your map image and define property coordinates.
4. Use `[plat_map id="POST_ID"]` on any page or template.

## Requirements

- WordPress 5.2+
- PHP 7.2+
- Estatik Real Estate Plugin
- Advanced Custom Fields (ACF)
