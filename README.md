Introduction

Welcome to the job-listings project! This tool was created to aggregate tech-related job postings across Europe while helping me deepen my understanding of SQL and Python development in a real-world scenario.

🔧 Tools: Python, MariaDB, Ubuntu Server (VPS), Cloudflare, WordPress (self-hosted), VS Code
Overview

What began as a simple learning exercise in SQL quickly expanded into a full-stack project involving Python scripts, a MySQL-compatible database, and a cloud-hosted front-end. The goal is to automatically collect, store, and display job listings from across Europe in the tech sector.

The website is hosted on a VPS and uses a custom Cloudflare-managed domain. While the back-end pipeline is mostly functional, the front-end and data categorization systems are still being improved. The site will continue to evolve with regular updates and feature enhancements.
Features

    Job Aggregation: Fetches European tech job postings through an API.

    SQL Storage: Stores relevant details in a structured SQL database.

    Snippet Previews: Captures short descriptions for quick previews.

    Link Tracking: Includes original source links for each listing.

    City Filtering: Prioritizes proper city name formatting for European locations.

Workflow Overview

The job aggregation system runs on a VPS and follows this core workflow:

    Fetching Jobs:

        Uses Python and the Jooble API to pull new job listings.

    Filtering and Cleaning:

        Parses and filters by region, language, and tech relevance.

        Ensures only valid European cities are considered.

    Database Storage:

        Stores all results in a MariaDB database.

        Tracks metadata like timestamps and source links.

    Website Integration:

        WordPress front-end connects with the back-end database.

        Displays job snippets and links, updated as often as possible.

What’s Next

The front-end design, user filtering, and advanced categorization (by skills, tools, or languages) are still a work in progress. Planned improvements include:

    Custom search and filter options.

    Admin panel for easier management.

    Weekly data visualizations and summaries.
