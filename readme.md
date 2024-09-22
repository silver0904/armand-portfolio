# Getting Started with Hugo Website

This guide will walk you through the steps to start this Hugo website.


## Step 1: Load the theme
    ```
    hugo mod tidy
    ```

## Step 2: Set up Node.js
    ```
    hugo mod npm pack
    npm install
    ```

## Step 3: Run the site
    ```
    hugo server -w
    ```
    Open your web browser and visit `http://localhost:1313` to view your Hugo website.

## Step 4: Deploy to AWS
    ```
    hugo deploy aws
    ```
