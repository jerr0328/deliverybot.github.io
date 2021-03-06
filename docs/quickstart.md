---
layout: page
title: Quickstart
---

# Quickstart

Deliverybot is a GitHub app, to get started with deployments we need a
repository and to install the Deliverybot app onto that repo. The below guide
will walk you through deploying deliverybot and getting an example repository
setup.

### 1. [Deploy the Deliverybot GitHub app][app]

Deploy the Deliverybot GitHub application to an infrastructure of your choice.

### 2. [Fork the example repository][example]{:target="_blank"}

Visit one of the example repositories and create a new fork:

- [Basic example that doesn't actually deploy][example]{:target="_blank"}.
- [GitOps example with FluxCD][example-gitops]{:target="_blank"}.
- [Helm example with actions and pr environments][example-helm]{:target="_blank"}.

### 3. Push a commit to watch the workflows kick off!

Go to your repository and push a commit.

### 4. [Install integrations][integrations]{:target="_blank"}

Install integrations like Slack or Helm to build a workflow for your team. Visit
our [integrations page][integrations]{:target="_blank"} for more information.

## Next

Once you have a working example read through the [guide](/docs/guide/) for more
information on how to setup complex workflows.

[app]: /docs/deploying/
[how]: /docs/how-it-works/
[example]: https://github.com/deliverybot/example
[example-helm]: https://github.com/deliverybot/example-helm
[example-gitops]: https://github.com/deliverybot/example-gitops
[integrations]: /integrations/
