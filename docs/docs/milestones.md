---
id: milestones
title: Milestones and Roadmap
---

## [v0.39.0](https://github.com/ory/oathkeeper/milestone/7)

*This milestone does not have a description.*

### [Bug](https://github.com/ory/oathkeeper/labels/bug)

#### Issues

* [ ] Integrate with Traefik, Nginx, Ambassador, Envoy ([oathkeeper#263](https://github.com/ory/oathkeeper/issues/263))
* [ ] Rule mutator template changes not reloaded after file update ([oathkeeper#272](https://github.com/ory/oathkeeper/issues/272))
* [ ] Log specified http request headers ([oathkeeper#361](https://github.com/ory/oathkeeper/issues/361))
* [ ] Timeout in oauth2_client_credentials when using self-signed certificates ([oathkeeper#368](https://github.com/ory/oathkeeper/issues/368))
* [ ] oauth2_introspection not parsing single string aud valie ([oathkeeper#491](https://github.com/ory/oathkeeper/issues/491))

### [Enhancement](https://github.com/ory/oathkeeper/labels/enhancement)

#### Issues

* [ ] Implement GRPC response handler in Decisions API ([oathkeeper#134](https://github.com/ory/oathkeeper/issues/134))
* [ ] Pass query parameters to the hydrator ([oathkeeper#339](https://github.com/ory/oathkeeper/issues/339))
* [ ] Switch to go-jose key generation lib ([oathkeeper#419](https://github.com/ory/oathkeeper/issues/419))
* [ ] Oathkeeper behind ssl terminating balancer ([oathkeeper#153](https://github.com/ory/oathkeeper/issues/153))

#### Pull Requests

* [ ] refactor: refactor decisions API and add traefik (#486) ([oathkeeper#487](https://github.com/ory/oathkeeper/pull/487)) - [@hackerman](https://github.com/aeneasr)

## [v1.0.0](https://github.com/ory/oathkeeper/milestone/2)

*This milestone does not have a description.*

### [Bug](https://github.com/ory/oathkeeper/labels/bug)

#### Issues

* [x] Adopt new Keto SDK ([oathkeeper#172](https://github.com/ory/oathkeeper/issues/172))

### [Enhancement](https://github.com/ory/oathkeeper/labels/enhancement)

#### Issues

* [x] TLS Termination 'X-Forwarded-Proto' ([oathkeeper#95](https://github.com/ory/oathkeeper/issues/95))
* [x] Provide an endpoint that allows to fetch configuration information ([oathkeeper#131](https://github.com/ory/oathkeeper/issues/131)) - [@hackerman](https://github.com/aeneasr), [@Patrik](https://github.com/zepatrik)
* [x] Adopt new Keto SDK ([oathkeeper#172](https://github.com/ory/oathkeeper/issues/172))
* [x] Add file watcher for config file ([oathkeeper#215](https://github.com/ory/oathkeeper/issues/215)) - [@hackerman](https://github.com/aeneasr)
* [x] Add file watcher for access rules ([oathkeeper#216](https://github.com/ory/oathkeeper/issues/216)) - [@hackerman](https://github.com/aeneasr)