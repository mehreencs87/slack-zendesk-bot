# Slack - Zendesk Integrations

To create a webtask url for this ticket using the wt CLI tools:

```bash
wt create ticket.js -s zendesk_api_token={token} -s zendesk_api_email={email} slack_command_token={token} -s slack_api_token={token} -s slack_icon_url={icon_url} -s zendesk_tenant={tenant} -s support_email={support_email}
```
