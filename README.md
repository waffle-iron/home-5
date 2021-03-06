# Jumpscale 9 Home Page

This home repository serves a starting point for people to find their way in all other repos in the JumpScale product organization.

JumpScale 9 is the descendant of [JumpScale8](JS8.md)

- Product Owners: [Reem](https://github.com/rkhamis) and [Kristof](https://github.com/despiegk)
- Kanban:
  - [JS9 Kanban](https://waffle.io/Jumpscale/home?source=Jumpscale%2Fays9,Jumpscale%2Fcore9,Jumpscale%2Fdeveloper,Jumpscale%2Flib9,Jumpscale%2Fportal9,Jumpscale%2Fprefab9)
- [Telegram](https://telegram.me/joinchat/Bb0WhAmxj5ZMhK2MZ7m2OQ)

# Table of contents
 - [Repos](#repos)
 - [Features](#features)
 - [Release Schedule](#roadmap)
 - [Documentation](#documentation)


## Repos:
**Code Repos**:
  - [Developer](https://github.com/Jumpscale/developer)
  - [core9](https://github.com/Jumpscale/core9)
  - [lib9](https://github.com/Jumpscale/lib9)
  - [prefab9](https://github.com/Jumpscale/prefab9)
  - [ays9](https://github.com/Jumpscale/ays9)
  - [portal9](https://github.com/Jumpscale/portal9)

**Tools Repos**:
- [AYS Build](https://github.com/Jumpscale/ays_build)
- [Dev Process Robot](https://github.com/Jumpscale/ays_gig_github_dev_process)
- [Telegram Buisness Tool](https://github.com/Jumpscale/telegram_biztool)
- [go-raml](https://github.com/Jumpscale/go-raml)

**Miscellaneous**:
- [Dockers](https://github.com/Jumpscale/dockers)
- [Atom plugins](https://github.com/Jumpscale/atom_plugins)


## Features
- Restructuring code base to be more modular.
- Documentation generation
- AYS (At Your Service)
- JSPortal
- Prefab
- CI
- Built completely in docker. See how to get started [here](https://github.com/Jumpscale/developer)

## Remarks
- only support python 3.5+
- support +- any linux distro + mac osx (windows not yet)

## Roadmap:
 * May 7, 2017: **[8.1.1](https://github.com/Jumpscale/jumpscale_core8/releases/tag/v8.1.1)** (released)
    - Current production release.
   
 * **8.1.2** (discontinued)
   - Put on roadmap.
   - Regarding [deploying Rogerthat through AYS](https://github.com/Jumpscale/ays_jumpscale8/issues/163)
   
   - Work archived in: [core](https://github.com/Jumpscale/jumpscale_core8/releases/tag/archive_8.1.2) and [AYS](https://github.com/Jumpscale/ays_jumpscale8/releases/tag/archive_8.1.2)
   
 * May 25, 2017: **[8.1.3](https://github.com/Jumpscale/jumpscale_core8/releases/tag/v8.1.3)** (released)
   - Based on 8.1.1
   - New feature: [AYS template for disk.ovc](https://github.com/Jumpscale/ays_jumpscale8/issues/231)
   
 * **8.2.0** (Discontinuted. Work moved to 9.0.0)
   - Mainly deals with cleanup of cuisine modules and a new version of AYS.
   - See [kanban](https://waffle.io/Jumpscale/home?milestone=8.2.0)

 * June 6, 2017: **[9.0.0](release_notes/9.0.0.md)** (released)
   - Release includes:
     - Restructuring JumpScale in a more modular architecture.
     - Introduces no new features.
  
 * June 22, 2017: **[9.0.3](release_notes/9.0.3.md)** (released)
   - Release includes:
     - Minor fixes for 9.0.0 and minor enhancements.
     - Set up CI for better quality and stability assurance
 
 * July 6, 2017: **[9.1.0](milestones/9.1.0.md)** (in progress)
    - Introduces:
       - support installation on multiple linux distributions as well as windows
       - Blueprints editor
       - Show progress of runs in AYS portal
       - Some AYS templates


  
## Documentation:

- To get started, see [developer](https://github.com/Jumpscale/developer)
- Core [docs](https://github.com/Jumpscale/core9/tree/master/docs)
- AYS [docs](https://github.com/Jumpscale/ays9/tree/master/docs)
- Prefab [docs](https://github.com/Jumpscale/prefab9/tree/master/docs)
- Portal [docs](https://github.com/Jumpscale/portal9/tree/master/docs)
