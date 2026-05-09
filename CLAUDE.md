# Shopify AI Toolkit

This project connects Claude Code to the Shopify store **urn-modern.myshopify.com** via the [Shopify AI Toolkit](https://github.com/Shopify/shopify-ai-toolkit) MCP server.

## Setup

### 1. Create a Shopify Admin API token

1. Go to your [Shopify Admin → Settings → Apps and sales channels](https://admin.shopify.com/store/urn-modern/settings/apps)
2. Click **Develop apps** (top right)
3. Click **Create an app**, name it anything (e.g. "Claude Code")
4. Under **Configuration**, click **Configure Admin API scopes** and enable the scopes you need (e.g. `read_products`, `write_products`, `read_orders`, etc.)
5. Click **Install app**, then copy the **Admin API access token**

### 2. Set the token in your environment

```bash
export SHOPIFY_ACCESS_TOKEN="shpat_xxxxxxxxxxxxxxxxxxxx"
