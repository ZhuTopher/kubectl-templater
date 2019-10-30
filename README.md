# kubectl-templater

At all my workplaces I've been at so far, each one had a differnt method of handling templating Kubernetes `yaml`s. Be it language-based templating (eg: Python Jinja vs. Mustache) or in-house programs/automation scripts I have yet to find a clean agreed upon solution.

Plan is to see if I can make a `kubectl` plugin (so it at least 'feels' native) to effectively template a yaml. If I find an existing tool which does this nicely, this repo will likely go away.

Some links to look into:
- https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/
- https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/
