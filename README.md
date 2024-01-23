# Website Hosting and Local Development Guide

This guide provides instructions for accessing the hosted versions of the website and setting up a local development environment.

## Hosted Versions

There are two hosted versions of the website available for viewing and use:

1. **Netlify Hosting**
   - Access the website hosted on Netlify at: [Netlify Hosting](https://gangli.netlify.app)

2. **GitHub Pages Hosting**
   - View the GitHub Pages hosted version at: [GitHub Hosting](https://ganglix.github.io/professional-academic-website/)

## Local Development Setup

To set up and run the website locally on your machine, follow these steps:

### Prerequisites

Ensure that you have [Conda](https://docs.conda.io/en/latest/) installed on your system for managing packages and environments.

### Steps for Local Setup

1. **Activate Conda Environment**
   - Open your terminal or command prompt.
   - Activate the Conda environment by running (base-2 is an environment name where hugo is installed):
     ```
     conda activate base-2
     ```

2. **Run Hugo Server**
   - Once the environment is activated, start the Hugo server with:
     ```
     hugo server
     ```
   - This will compile the website and host it on a local server. 

### Accessing Locally Hosted Site

- After starting the Hugo server, the terminal will display a local URL (usually `http://localhost:1313/`). Open this URL in your web browser to view the website.
