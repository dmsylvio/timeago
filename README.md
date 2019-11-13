# Time Ago plugin for Craft CMS 3.x

Time Ago twig filter

## Requirements

This plugin requires Craft CMS 3.0.0 or later.

## Installation

To install the plugin, follow these instructions.

1. Open your terminal and go to your Craft project:

        cd /path/to/project

2. Then tell Composer to load the plugin:

        composer require dmsylvio/timeago

3. In the Control Panel, go to Settings → Plugins and click the “Install” button for Time Ago.

## Using Time Ago

        {{ entry.postDate|time_ago }}