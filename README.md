# Datadog Agent builders

This repo contains the Dockerfiles of the images used to build the rpm and deb
packages for the Datadog [Agent][agent].

## How to use

You can follow [these instruction][agent-omnibus] to build a package locally:
please notice rpm packages are signed, so you won't be able to exactly reproduce
the same artifact that's distributed through the official Yum repository.

[agent]: https://github.com/DataDog/datadog-agent
[agent-omnibus]: https://github.com/DataDog/datadog-agent/blob/master/docs/dev/agent_omnibus.md