# Assign Desktop releases

This public repository distributes signed Assign Desktop installers, updater
artifacts, checksums, and channel metadata. The closed-source application code
lives in a separate private repository and is never committed here.

Release tags are immutable unprefixed Semantic Versions. The
`desktop-stable` and `desktop-candidate` releases are mutable channel pointers:
their `latest.json` assets are promoted only after every supported platform
artifact and updater signature has been published successfully.

Do not commit installer binaries to this Git repository. Release assets are the
only supported binary storage boundary.
