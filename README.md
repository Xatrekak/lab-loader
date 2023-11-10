# ntbg.app

Welcome to the official repository for ntbg.app, a dynamic wallpaper service that taps into the extensive library of wallhaven.cc. Our API serves up wallpapers across the spectrum of SFW to NSFW, depending on your preferences and the time of day.
Features

    Auto-adjusting wallpapers based on the time of day and your timezone.
    Filtering options to select from SFW, Sketchy, and NSFW content.
    Simple API endpoints for easy access and integration.
    No API key required for SFW and PG-13 content.

# Endpoints

Here's how you can use the available endpoints:

    /auto: Get a wallpaper that adjusts NSFW level based on the timezone.
    /all: Fetch a random wallpaper from all categories (API key needed for NSFW).
    /nsfw: Strictly NSFW wallpapers (API key required).
    /pg13: Slightly NSFW (PG-13) wallpapers, no API key required.
    /: Default endpoint for SFW wallpapers.

# Usage

Each endpoint redirects to a wallpaper URL from wallhaven.cc. To use an endpoint, simply append it to the base URL https://ntbg.app followed by the required parameters.

Example:

https://ntbg.app/auto?apikey=YOUR_API_KEY&timezone=YOUR_TIMEZONE

# API Key

An API key is necessary if you want to include NSFW results. Please visit wallhaven.cc to obtain your API key.

# Contributions

Contributions are welcome! If you have any suggestions or improvements, please feel free to fork the repository and submit a pull request.
Feedback

If you have any feedback or run into issues, please file an issue on GitHub, and we'll get back to you as soon as possible.
