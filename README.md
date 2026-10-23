# DriftSeal canary

A deliberately tiny, non-functional component used by mAIb Tech to test
[DriftSeal](https://drift.maib.io) drift detection end to end. It is not an MCP
server, contains no executable code, and should not be installed or used.

`tools.json` is changed on purpose during acceptance tests so that DriftSeal
has a controlled change to detect.
