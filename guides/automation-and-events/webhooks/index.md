---
rank: 1
id: automation-and-events/webhooks/index
cId: automation-and-events
scId: automation-and-events/webhooks
isIndex: true
---

# Webhooks

Webhooks enable you to attach event triggers to Box files and folders.

Event triggers monitor when events happen on items and then notify your
application when they occur by sending a HTTP requests to a URL of your choice.

Because every aspect of webhooks can be controlled through the API your
application can create webhooks on files and folders as they're needed and
remove them when they are no longer needed.

## Scopes & Permissions

Please ensure you have the "manage webhooks" application scope enabled in the
configuration tab of the developer console for your application or you will
receive a `403` error when trying to make API calls.