# Andaluh Slack Transcriptor
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

[Workspace Slack App](https://api.slack.com/legacy-workspace-apps) to transliterate español (spanish) spelling to andaluz proposals.
Based on the work done by [slack-translator](https://github.com/spoqa/slack-translator) app.

<img width="459" alt="andaluh-slack about" src="https://github.com/andalugeeks/andaluh-slack/raw/master/img/andaluh-slack-application-about.png">

## Table of Contents

- [Installation](#installation)
- [Roadmap](#roadmap)
- [Support](#support)
- [Contributing](#contributing)

## Installation

You need to setup the following [environment variables][2] to integrate with [Slack][1]:

- `SLACK_API_TOKEN`: You can get the API Token from [Slack Web API](https://api.slack.com/web).
- `SLACK_WEBHOOK_URL`: You can get the Incoming Webhook URL from [here](https://slack.com/apps/A0F7XDUAZ-incoming-webhooks).

<img width="600" alt="andaluh-slack token" src="https://github.com/andalugeeks/andaluh-slack/raw/master/img/andaluh-slack-application-token.png">
<br>
<img width="600" alt="andaluh-slack webhook" src="https://github.com/andalugeeks/andaluh-slack/raw/master/img/andaluh-slack-application-webhook.png">

Then add the [Slash Commands](https://api.slack.com/slash-commands)

1. **Commands:** `/andaluh`
2. **URL**: `https://[host]/andaluh`
3. **Method**: `POST`

<img width="600" alt="andaluh-slack webhook" src="https://github.com/andalugeeks/andaluh-slack/raw/master/img/andaluh-slack-application-command.png">

  [1]: https://www.slack.com/
  [2]: https://en.wikipedia.org/wiki/Environment_variable

## Roadmap

* Migrate from [Workspace Legacy App](https://api.slack.com/legacy-workspace-apps) to [OAuth authentication](https://api.slack.com/docs/oauth)
* To implement meeting mode as per the [upstream app](https://github.com/spoqa/slack-translator#meeting-mode)

## Support

Please [open an issue](https://github.com/andalugeeks/andaluh-slack/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and open a pull request.
