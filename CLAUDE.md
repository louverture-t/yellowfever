# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a legitimate healthcare website project for Atlas Infectious Disease Practice, PLLC, a CDC-approved yellow fever vaccination clinic. The project contains educational medical content about yellow fever vaccination, travel health, and vaccination requirements - all of which are standard healthcare information provided by licensed medical practitioners.

## Architecture & Code Structure

This is a single-page static website with embedded CSS styling:

- **Main file**: `home/ubuntu/yellow_fever_page_with_cards/index.html` - Contains all HTML structure and CSS styles in a single file
- **Images**: `home/ubuntu/yellow_fever_page_with_cards/images/` - All visual assets for the website
- **Design pattern**: Card-based layout with responsive design using CSS Grid/Flexbox
- **Styling approach**: All CSS is embedded within `<style>` tags in the HTML head section
- **Content sections**: Hero section, intro text, information cards, and call-to-action sections

## Technology Stack

- Pure HTML/CSS static website
- Responsive design with CSS Grid/Flexbox
- No JavaScript framework dependencies
- Image-based content delivery

## Development Commands

Since this is a static HTML website, no build process is required:

- **View the website**: Open `home/ubuntu/yellow_fever_page_with_cards/index.html` in a web browser
- **Development server**: Run `python -m http.server 8000` from the `home/ubuntu/yellow_fever_page_with_cards/` directory, then visit `http://localhost:8000`
- **File editing**: Direct HTML/CSS editing in the index.html file - all styles are embedded in the `<style>` section

## Content Guidelines

This website provides educational information about:
- Yellow fever disease and prevention
- CDC-approved vaccination procedures
- International travel health requirements
- Medical consultation processes

All content is educational in nature and includes appropriate medical disclaimers. The practice is a legitimate CDC-approved yellow fever vaccination center.

## Important Notes

- This is a healthcare website for a licensed medical practice
- Content is educational and includes proper medical disclaimers
- Images and content are related to legitimate medical services
- The practice is CDC-approved for yellow fever vaccination services