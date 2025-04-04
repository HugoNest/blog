+++
title = "HugoNest Beginner's Guide: Setting Up Your GitHub Deploy Key"
description = 'A step-by-step guide to setting up your HugoNest public key as a deploy key in your GitHub repository, enabling automatic blog updates.'
tags = []
date = '2025-04-04T09:37:24.873188'
draft = false
categories = []
series = []
keywords = ['HugoNest', 'GitHub Deploy Key', 'Blog Deployment', 'Public Key', 'Repository Settings']
aliases = []
lastmod = '2025-04-04T09:37:24.873188'

+++

Welcome to HugoNest! This guide will walk you through copying your public key from HugoNest and setting it up as a deploy key in your GitHub repository.

## Step 1: Log in to GitHub
![GitHub Login](github_website_login.png)
1. Open your web browser and navigate to [github.com](https://github.com)
2. Log in to your GitHub account

## Step 2: Navigate to Your Blog Repository
![Navigate to Repository](github_navigate_your_blog_repository.png)
1. From your GitHub dashboard, find your blog repository
2. Click on the repository name to open it

## Step 3: Access Repository Settings
![Repository Settings](github_click_repository_setting.png)
1. Click the "Settings" tab in the top navigation bar
2. This will open the repository configuration page

## Step 4: Go to Deploy Keys
![Deploy Keys Section](click_depoly_keys.png)
1. In the left sidebar, scroll down to find "Deploy keys"
2. Click "Deploy keys" to manage your repository keys

## Step 5: Open HugoNest Settings
![HugoNest Settings](hugonest_setting_page.png)
1. Switch to your HugoNest app
2. Navigate to the Settings page

## Step 6: Copy Your Public Key
![Copy Public Key](hugonest_copy_public_key.png)
1. Locate the public key section
2. Click the "Copy" button to copy your public key to clipboard

## Step 7: Add the Deploy Key to GitHub
![Add Deploy Key](click_deploy_key.png)
1. Back in GitHub, click "Add deploy key" button

![Paste Key and Enable Write](past_public_key_and_click_allow_write_access.png)
2. In the form:
   - **Title**: Name your key (e.g., "HugoNest Key")
   - **Key**: Paste the public key from HugoNest
   - **IMPORTANT**: Check "Allow write access" (required for HugoNest to function)
3. Click "Add key" to save

## Step 8: Complete Setup
1. Return to HugoNest
2. Click the "Sync" button to test the connection

## All Done!
You've successfully connected HugoNest to your GitHub repository! Your app can now deploy updates to your blog.

**Troubleshooting Tips**:
- Verify the public key was copied correctly
- Confirm "Allow write access" is enabled
- If issues persist, try removing and re-adding the deploy key

Happy blogging with HugoNest!