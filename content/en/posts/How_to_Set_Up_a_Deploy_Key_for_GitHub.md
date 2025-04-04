+++
title = 'How to Set Up a Deploy Key for GitHub'
description = 'A step-by-step guide on setting up a deploy key in GitHub to securely grant SSH access to a single repository without using personal account credentials.'
tags = ['GitHub', 'SSH', 'Deploy Keys', 'HugoNest']
date = '2025-04-04T09:07:29.738845'
draft = false
categories = ['Tutorials', 'GitHub']
series = ['GitHub Security', 'HugoNest Project']
keywords = ['GitHub deploy key', 'SSH access', 'repository security', 'GitHub settings', 'secure deployment']
aliases = []
lastmod = '2025-04-04T09:07:29.738845'

+++

# How to Set Up a Deploy Key for GitHub

Deploy keys in GitHub provide a secure way to grant SSH access to a single repository without using personal account credentials. This guide will walk you through the simple process of setting up a deploy key.

## Step-by-Step Instructions

### Navigate to Repository Settings
1. Go to your GitHub repository.
2. Click on the "Settings" tab in the top navigation bar.
   ![](https://easy-hugo.github.io/images/how-to-set-up-a-deploy-key-for-github/1.png)

### Access Deploy Keys Section
1. In the left sidebar, find and click on "Deploy Keys."
   ![](https://easy-hugo.github.io/images/how-to-set-up-a-deploy-key-for-github/2.png)

### Add a New Deploy Key
1. Click the "Add deploy key" button (green button on the right side).
   ![](https://easy-hugo.github.io/images/how-to-set-up-a-deploy-key-for-github/3.png)

### Configure Your Key
1. In the "Title" field, enter a descriptive name for this key (e.g., "Production Server").
2. Check the "Allow write access" box if you need write permissions.
3. For read-only access, leave this unchecked (recommended for most use cases).
   ![](https://easy-hugo.github.io/images/how-to-set-up-a-deploy-key-for-github/4.png)

### Save the Key
1. Click "Add key" to complete the setup.

## Important Notes
- Deploy keys are tied to a specific repository.
- You must have admin access to the repository to add deploy keys.