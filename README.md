# Automate API Testing with Newman

This repository demonstrates how to automate API testing using **Newman**, the command-line tool for running Postman collections. The API tests are executed using the **KasirAja** Postman collection.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Setup Instructions](#setup-instructions)
3. [Running Tests](#running-tests)

## Prerequisites

Before you can run the tests, you need to have:

- **Node.js**: [Download Node.js](https://nodejs.org/)
- **Newman**: Install Newman globally using npm:

      npm install -g newman

## Setup Instructions

### Step 1: Clone the Repository
Clone the repository to your local machine:

    git clone https://github.com/ZulvikaK/postman-api-kasiraja.git
    cd postman-api-kasiraja

### Step 2: Install Newman (if not installed)
Install Newman globally if you haven't yet:

npm install -g newman

### Step 3: Verify Installation
Check if Newman is installed correctly:

    newman --version

## Running Tests

### Step 1: Run the Tests Locally
Run the tests using the following command:

    newman run KasirAja.postman_collection.json -e KasirAjaMySkill.postman_environment.json

### Step 2: Run the Tests with HTML Report
Generate an HTML report after running the tests:

    newman run KasirAja.postman_collection.json -e KasirAjaMySkill.postman_environment.json -r html --reporter-html-export newman-report.html

## Result of Automation Testing for KasirAjaApi using Newman
[ResultNewman](https://www.notion.so/Result-of-Automation-Testing-for-KasirAjaApi-using-Newman-175c4a53b333809295d0d558b4da8f12?pvs=4)
