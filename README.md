# DEV APPS

A bunch of docker containers that help me run all relevant services locally <sup>(tested on MacOS)</sup> for development/testing purposes.

## Prerequisites

---

### Docker + Docker Compose

[SITE](https://www.docker.com) | [DOCS](https://docs.docker.com)

> Docker takes away repetitive, mundane configuration tasks and is used throughout the development lifecycle for fast, easy and portable application development – desktop and cloud. Docker’s comprehensive end to end platform includes UIs, CLIs, APIs and security that are engineered to work together across the entire application delivery lifecycle.

Duh!

---

### Helm - Hosts File Manager

[DOCS](https://gotomorrow.dev/docs/Helm) | [App Store](https://apps.apple.com/se/app/helm-hosts-file-manager/id1099472017?l=en&mt=12)

> Helm is a simple hosts file manager. You can set whether the title bar is transparent or not in the preferences. Keep the status bar running can be set in preferences.

Helm is used to easily manage hosts file (`/etc/hosts`) entries.

---

### Caddy

[SITE](https://caddyserver.com) | [DOCS](https://caddyserver.com/docs/)

> Caddy is a powerful, extensible platform to serve your sites, services, and apps, written in Go.

Caddy simplifies setting up virtual hosts for the apps, so that they can be served over HTTPS on a local domain.

See [`Caddyfile`](./Caddyfile).

## Apps

---

### Portainer | [&#128279;](https://portainer.dd/)

[SITE](https://portainer.io/) | [DOCS](https://docs.portainer.io/) | [GITHUB](https://github.com/portainer/portainer)

> Portainer hides the complexity of managing containers behind an easy-to-use UI. By removing the need to use the CLI, write YAML or understand manifests, Portainer makes deploying apps and troubleshooting problems so easy that anyone can do it.

Portrainer provides a nice interface to manage everything container-related.

---

### Verdaccio | [&#128279;](https://npm.dd/)

[SITE](https://verdaccio.org) | [DOCS](https://verdaccio.org/docs/what-is-verdaccio) | [GITHUB](https://github.com/verdaccio/verdaccio)

> Verdaccio is a lightweight private npm proxy registry built in Node.js

A local npm proxy to keep npm packages private until they are ready to be published.

Additional [notes](./docs/verdaccio.md).

---
