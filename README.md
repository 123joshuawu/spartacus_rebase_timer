# spartacus_rebase_timer

Discord bot for showing spartacus.finance rebase timer.

Retrieves the current block every minute (default) and calculates the remaining time based on the BLOCK_RATE_SECONDS.

## Setup

All you need is a discord token to use the bot.

Add a .env file with the token specified as TOKEN=

## Config (optional)

Can also optionally configure certain parameters using the environment variables:
- UPDATE_INTERVAL_MS: ms Interval to update the timer (default 1 minute)
- EPOCH_INTERVAL: length of one epoch (default 33100)
- BLOCK_RATE_SECONDS: rate of blocks/sec (default 0.87)
