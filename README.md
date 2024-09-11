# Medusa Local Installation Guide

This guide will walk you through the steps to install and run Medusa locally.

## Prerequisites

Before you begin, make sure your system meets the following prerequisites:

- **Node.js**: Version 16 or higher is required. You can download it [here](https://nodejs.org/).
- **Backend Database**: Medusa requires a PostgreSQL database by default, but you can also use **Supabase** as an alternative. You will need to modify the Medusa config file for this.

## Steps to Install and Run Medusa

### 1. Install Medusa CLI

Run the following command to globally install the Medusa CLI:

```bash
npm install @medusajs/medusa-cli -g
```

### 2. Create New Project

``` bash
medusa new my-medusa-store
```

### 3. Start the Medusa 

```bash
medusa develop
```

### 4. Check if it's running

```bash
curl localhost:9000/store/products
```
