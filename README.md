# gitops-demo-apps

Manifests for all our demo-apps go in here

These are kept separate from the application code to decouple them

# demo features

New demo images in dockerhub will fire a webhook to circleCI which will update
the demo manifest with a new image digest and raise a PR

This requires human approval !

-> See gitops-argocd-apps to see how this gets deployed
