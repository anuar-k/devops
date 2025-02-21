# GitLab Runner Helm Chart

TOKEN=RLs59uf39x1CtGtEs7ey
helm upgrade --install --create-namespace -n gitlab-runner gitlab-runner --set gitlabUrl=https://git.bildme.ru,runnerRegistrationToken=$TOKEN k8s/gitlab-runner
