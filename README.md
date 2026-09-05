A hugo module to implement [FEP-b06c: Activitypoll](https://codeberg.org/fediverse/fep/src/branch/main/fep/b06c/fep-b06c.md).

To use, add this to your `config.toml`:
```toml
[[module.imports]]
path = "github.com/sams96/hugo-activitypub"

[outputs]
home = [
  "HTML",
  "RSS",
  "ActivityPubActor",
  "ActivityPubInbox",
  "ActivityPubOutbox",
  "WebFinger"
]
page = [ "HTML", "ActivityPubNote" ]
```

See also: https://socialwebfoundation.org/2026/09/04/static-activitypub-publishing/
