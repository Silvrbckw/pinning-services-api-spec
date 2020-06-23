# Pinning Service API Specifications

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://protocol.ai)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](https://ipfs.io/)
![](https://img.shields.io/badge/status-wip-orange.svg?style=flat-square)

> This repository contains the specs for the vendor-agnostic pinning service API for the IPFS ecosystem

- [About](#about)
- [Timeline](#timeline)
- [Contribute](#contribute)

## About

A Pinning Service is a service that accepts [CIDs](https://github.com/ipld/cid/) from a user and will host the data associated with them.

The rationale behind defining a generic pinning service API is to have a baseline functionality and interface that can be provided by these services so that tools can be built on top of a common base of functionality.



## Timeline

- 2019 Q2 
  - Creation of a generic Pinning Service API proposed in [ipfs/notes/issues/378](https://github.com/ipfs/notes/issues/378)
- 2020 Q2
  - Pinning Summit 2020 ([website](https://ipfspinningsummit.com/), [recorded talks](https://www.youtube.com/watch?v=rYD2lfuatJM&list=PLuhRWgmPaHtTvsxuZ9T-tMlu_v0lja6v5))
- 2020 Q3
  - [ipfs/pinning-services-api-specs](https://github.com/ipfs/pinning-services-api-specs) is created as a place for stakeholders to collaborate and finalize the spec
  - IPFS GUI Team looking into adding support for Pinning Services into Desktop apps ([ipfs-webui](https://github.com/ipfs-shipyard/ipfs-webui/)/[ipfs-desktop](https://github.com/ipfs-shipyard/ipfs-desktop))
    - **[WIP]** Analysis of Remote Pinning Services vs the needs of IPFS WebUI 


## Contribute

Suggestions, contributions, criticisms are welcome. Though please make sure to familiarize yourself deeply with IPFS, the models it adopts, and the principles it follows.
This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

### Spec lifecycle

We use the following label system to identify the state of this spec:

- ![](https://img.shields.io/badge/status-wip-orange.svg?style=flat-square) - A work-in-progress, possibly to describe an idea before actually committing to a full draft of the spec.
- ![](https://img.shields.io/badge/status-draft-yellow.svg?style=flat-square) - A draft that is ready to review. It should be implementable.
- ![](https://img.shields.io/badge/status-reliable-green.svg?style=flat-square) - A spec that has been adopted (implemented) and can be used as a reference point to learn how the system works.
- ![](https://img.shields.io/badge/status-stable-brightgreen.svg?style=flat-square) - We consider this spec to close to final, it might be improved but the system it specifies should not change fundamentally.
- ![](https://img.shields.io/badge/status-permanent-blue.svg?style=flat-square) - This spec will not change.
- ![](https://img.shields.io/badge/status-deprecated-red.svg?style=flat-square) - This spec is no longer in use.
