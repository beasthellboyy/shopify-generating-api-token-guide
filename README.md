Shopify API Token Generation Guide

Overview

This repository provides a Shopify PHP app template for testing API token generation. It is designed to work with Polaris UI and can benefit from the assistance of an LLM chatbot for additional support. The repository is forked from nyalex/shopify-generating-api-token-guide and contains updates and modifications.

Features

Shopify PHP App template

API token generation

API calls to write products

Includes installation and setup files

Compatible with Polaris UI

Files Included

README.md - Documentation for the project

api_call_write_products.php - Script for making API calls to write products

generate_token.php - Handles API token generation

install.php - Installation script

inc/ - Contains additional dependencies and configurations

Prerequisites

Ensure you have the following before running the app:

A Shopify Partner or Developer account

PHP installed on your system

Composer (for managing dependencies)

Installation

Clone the repository:

git clone https://github.com/beasthellboyy/shopify-generating-api-token-guide.git
cd shopify-generating-api-token-guide

Install dependencies:

composer install

Configure Shopify API credentials in generate_token.php.

Run the PHP server:

php -S localhost:8000

Access the app via http://localhost:8000

Usage

Modify generate_token.php with your Shopify API credentials.

Use api_call_write_products.php to test writing products via API.

Follow Shopify documentation for additional customization and integration.

Additional Resources

For more details, refer to Shopify's official documentation: Shopify API Docs

Contributions

Feel free to fork and contribute to enhance the project!

License

This project follows the same license as the original fork.
