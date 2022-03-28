# Slack Boltjs Starter

Deploy a Slack Bot onto Cyclic using Boltjs framework.

[![Deploy to Cyclic](https://deploy.cyclic.app/button.svg)](https://deploy.cyclic.app/)

## Setup

1. Deploy this starter
   - Copy the app URL for use when creating the slack app
1. Create Slack App
   - Follow this quick start to create a Slack App (aka bot): https://api.slack.com/start/building/bolt-js
   - The events url is the URL of your app with `/slack/events`
   - Example: `https://some-fun-animal.cyclic.app/slack/events/`
1. Set secret values
   - Copy your secret values to an `.env` file in your fork of this repo
   - Copy your secret values your Cyclic App
1. Confirm Events URL
   - You will need to set the secret values before you can register your events url

### Example Secret Values

```toml
SLACK_SIGNING_SECRET=somelongalphanumericwithouthyphens
SLACK_BOT_TOKEN=xoxb-some-long-alpha-numeric-with-hyphens
```

## Further References

- Slack Boltjs Concepts: https://slack.dev/bolt-js/concepts
- Slack Dev console: https://api.slack.com/apps
