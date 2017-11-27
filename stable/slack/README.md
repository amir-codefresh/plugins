# Codefresh Helm Plugin

Use Codefresh Slack plugin to send a message to a channel.

## Usage


```yaml
---
version: '1.0'

steps:

  ...

  publish_to_repo:
    image: codefresh/slack-message-sender

  ...

```

## Environment Variables

- **required** `WEBHOOK_URL` - Url to the channel. Slack official [docs](https://api.slack.com/incoming-webhooks)
- `DEBUG` - print verbose output