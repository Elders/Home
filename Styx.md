# Styx

### The future of these projects is not clear. There are two possible paths from here - [![Olympus](https://img.shields.io/badge/Status-olympus-green.svg)](Olympus.md) or [![Tartarus](https://img.shields.io/badge/Status-tartarus-red.svg)](Tartarus.md) 

## List of projects that are ![Styx](https://img.shields.io/badge/Status-styx-orange.svg)

### Cronus 
- [Cronus.Serialization.Proteus](https://github.com/Elders/Cronus.Serialization.Proteus) - this has been the preferred serialization with Cronus v2. However, there is a huge warm up performance hit with big projects which needs to be resolved. Despite this, it works really fast. The implementation has small protocol changes
- [Cronus.Projection.ElasticSearch](https://github.com/Elders/Cronus.Projection.ElasticSearch) - builds projections dynamically. Very useful for projects which just started and changes occur frequently. However, it must be switched to another persister such as Cassandra after the initial stages of the project