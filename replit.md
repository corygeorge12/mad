# Project Overview

This is a simple static HTML redirect page imported from GitHub (https://github.com/corygeorge12/mad).

## Purpose
The page decodes a base64-encoded email from the URL hash parameter and redirects to an IPFS link with the decoded email.

## Architecture
- **Type**: Static HTML page
- **Files**: Single `index.html` file
- **No dependencies**: Pure HTML/JavaScript, no build system or package manager needed

## How It Works
1. User visits the page with a hash parameter (e.g., `#base64EncodedEmail`)
2. JavaScript extracts and decodes the base64 string
3. Redirects to an IPFS link with the decoded email appended

## Recent Changes
- **2025-11-01**: Initial import and Replit environment setup
  - Configured simple HTTP server for static content
  - Set up workflow to serve on port 5000
  - Deployment configured for autoscale
