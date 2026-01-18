# EVURO-park
Urban dog walking and date 

## Configuration

### CZf API Setup

This project requires CZf API credentials to function properly.

1. Copy the example environment file:
   ```bash
   cp .env.example .env
   ```

2. Edit `.env` and add your actual CZf API credentials:
   - `CZF_API_KEY`: Your CZf API key
   - `CZF_API_SECRET`: Your CZf API secret

3. The `.env` file is automatically excluded from version control to keep your secrets safe.

**Important**: Never commit the `.env` file with actual credentials to the repository.
