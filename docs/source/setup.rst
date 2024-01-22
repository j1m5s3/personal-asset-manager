**Setup (Coinbase)** 
============================================

# Coinbase API Key Setup

This guide will walk you through the process of creating an API key on Coinbase. This is mainly needed for PAM trading strategies and some yield strategies.

## Steps

1. **Log in to Coinbase:**
   - Visit [Coinbase](https://www.coinbase.com/) and log in to your account.

2. **Navigate to API Settings:**
   - Once logged in, go to your account settings.

3. **Go to API Access:**
   - In your account settings, find and click on the "API Access" or "API Settings" tab.

4. **Create a New API Key:**
   - Look for an option to create a new API key. This might be labeled as "Create New API Key" or something similar.

5. **Configure API Key Permissions:**
   - Choose the permissions you want to grant to the API key. Ensure that the key has the necessary permissions for your intended use.

6. **Generate API Key:**
   - Click the "Generate API Key" or similar button to create your new API key.

7. **Copy API Key and Secret:**
   - After generating the key, you will be provided with an API key and API secret. Copy both of these as you won't be able to see the secret again.

8. **Store API Key Securely:**
   - Store your API key and secret securely. Do not share them publicly or expose them in your code.

9. **Add API Key to Your Application:**
   - Integrate the API key into your application code following Coinbase's API documentation.

10. **Additional Info:**
   - Ensure account is funded with > 0 units of the asset you want PAM to trade
   - Ensure account is funded with enough cash for your configured PAM trading service

## Security Tips

- Keep your API key and secret confidential.
- Regularly review your API access and revoke any unused keys.
- Consider creating separate keys for different purposes or environments.

## Resources

- [Coinbase API Documentation](https://developers.coinbase.com/)

**Setup (Discord)**
============================================

# Discord Webhook Setup

This guide will help you set up a Discord webhook for integrating with external services. **It is assumed that you have an existing discord account.**

## Steps

1. **Create a Discord Channel:**
   - If you don't have a channel yet, create one in your Discord server where you want the webhook messages to appear.

2. **Go to Channel Settings:**
   - Right-click on the channel and select "Edit Channel."

3. **Navigate to Webhooks:**
   - In the channel settings, go to the "Webhooks" tab.

4. **Create a New Webhook:**
   - Click the "Create Webhook" button.

5. **Customize Webhook:**
   - Choose a name for your webhook.
   - Optionally, upload an avatar for the webhook.
   - Copy the webhook URL.

6. **Save Webhook:**
   - Click the "Save" or "Create" button to create the webhook.

7. **Secure Webhook URL:**
   - Treat the webhook URL like a password. Do not share it publicly or expose it in your code.

8. **Add Webhook to Your Application:**
   - Integrate the webhook URL into your application code, API, or service to send messages to your Discord channel.

## Security Tips

- Keep your webhook URL confidential.
- Regularly review your webhooks and delete any unused ones.
- Consider creating separate webhooks for different purposes or services.

## Resources

- [Discord Webhooks Documentation](https://discord.com/developers/docs/resources/webhook)

