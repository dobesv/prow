---
title: "Hook"
weight: 30
description: >
  Describes the hook service
---

The Hook service receives events over HTTP and processes them using the configured [plugins][plugins].

For information on how to register hook as a [GitHub Webhook][github-webhook], refer to the [Prow deployment instructions][getting-started-deploy].

For more information on how hook fits into the job lifecycle, look at the [life of a prow job][life-of-a-prow-job].


[github-webhook]: https://developer.github.com/webhooks/
[plugins]: https://docs.prow.k8s.io/docs/components/plugins/
[getting-started-deploy]: https://docs.prow.k8s.io/docs/getting-started-deploy/
[life-of-a-prow-job]: https://docs.prow.k8s.io/docs/life-of-a-prow-job/
