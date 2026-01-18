# EVURO-park
Urban dog walking and date 

## Configuration

### Cloudflare API Setup

This project uses Cloudflare API for various services. To configure:

1. **Copy the environment template:**
   ```bash
   cp .env.example .env
   ```

2. **Get your Cloudflare API credentials:**
   - Go to [Cloudflare Dashboard](https://dash.cloudflare.com/profile/api-tokens)
   - Create a new API token or use an existing one
   - Copy your API token

3. **Update the `.env` file:**
   - Replace `your_cloudflare_api_token_here` with your actual API token
   - Optionally, add your Account ID and Zone ID if needed

4. **Security Note:**
   - The `.env` file is excluded from version control via `.gitignore`
   - Never commit your actual API credentials to the repository
   - Keep your API tokens secure and rotate them regularly

### Environment Variables

- `CF_API_TOKEN` - Your Cloudflare API token (required)
- `CF_ACCOUNT_ID` - Your Cloudflare account ID (optional)
- `CF_ZONE_ID` - Your Cloudflare zone ID (optional)

