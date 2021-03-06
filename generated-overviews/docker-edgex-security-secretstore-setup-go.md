<!--

********************************************************************************

WARNING:

    DO NOT EDIT.  THIS FILE IS AUTO-GENERATED

********************************************************************************

-->
**This image is ARCHIVED and no longer actively developed or maintained in EdgeX Foundry.  Use only when working with an older version of EdgeX.**
# Quick reference

- Maintained by: [EdgeX Foundry](https://www.edgexfoundry.org) (a [Linux Foundation](https://www.linuxfoundation.org/) project)

- Where to get help: [EdgeX Web Site](https://www.edgexfoundry.com), [EdgeX Documentation](https://docs.edgexfoundry.com), [EdgeX Slack](https://slack.edgexfoundry.org/), [EdgeX Project Wiki](https://wiki.edgexfoundry.org)
# Supported tags and respective Dockerfile links

- Hanoi
    - 1.3.0        - [Dockerfile](https://github.com/edgexfoundry/edgex-go/blob/hanoi/cmd/security-secretstore-setup/Dockerfile)

# Quick reference (cont.)

- Where to file issues: https://github.com/edgexfoundry/edgex-go/issues (NOTE - this image is archived and issues are no longer being worked)

- Supported architectures: intel/amd64

- Published image artifact details: https://nexus3.edgexfoundry.org

- Source of this description: https://github.com/edgexfoundry/edgex-docker-hub-documentation

# What is EdgeX Foundry?

EdgeX Foundry is a vendor-neutral, open source project hosted by The Linux Foundation building a common open framework for IoT edge computing.  At the heart of the project is an interoperability framework hosted within a full hardware and OS agnostic reference software platform to enable an ecosystem of plug-and-play components that unifies the marketplace and accelerates the deployment of IoT solutions.

In simple terms, EdgeX is edge middleware - serving between physical sensing and actuating "things" and our information technology (IT) systems.

EdgeX's official documentation can be found at [docs.edgexfoundry.org](https://docs.edgexfoundry.org).

![logo](https://www.lfedge.org/wp-content/uploads/2020/11/Screen-Shot-2019-10-28-at-3.45.29-PM-300x269.png)

*Edgey - the official EdgeX Foundry project mascot*
# What's in this image?

**ARCHIVED**
This image contains the EdgeX security-secretstore-setup service (aka edgex-vault-worker). The container relies on the security-secrets-setup container to create the PKI, in which the requirements of TLS in a single box are no more. security-secretstore-setup service also fork/execs security-file-token-provider to create the tokens, and adds shared secrets to Vault itself.  It was replaced by [docker-security-secretstore-setup-go](https://hub.docker.com/r/edgexfoundry/docker-security-secretstore-setup-go).  It is no longer used or supported.

The service source code: https://github.com/edgexfoundry/edgex-go

# License

View [license information](https://docs.edgexfoundry.org/1.3/#apache-2-license) for the software contained in this image.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.

Some additional license information which was able to be auto-detected might be found in the Attribution.txt file located in the image and copied from the associated


[source repository](https://github.com/edgexfoundry/edgex-go/blob/hanoi/cmd/security-secretstore-setup/Attribution.txt).