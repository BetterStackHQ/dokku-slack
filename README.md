# dokku-slack
A Slack notifier for Dokku

## Installation

```sh
# dokku 0.4+
$ dokku plugin:install https://github.com/wallmine/dokku-slack.git
```

## Commands

```sh
$ dokku help
  slack:set <app> <webhook>, Enable Slack notifications for app.
  slack:clear <app>, Disable Slack notifications for app.
  slack:get <app>, Print Slack notification settings for app.
```

To get **WebHook URL** you need to create a new
[**Incoming WebHook integration**](https://slack.com/services/new/incoming-webhook).
