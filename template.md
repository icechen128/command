---
title: How to delete all containers at once in docker
description: "When using docker we may create a lot of containers, it will be very slow to delete one by one, you can delete all the containers at once by combining commands."
date: August 25 2022
author: cmdhelp
authorUrl: https://github.com/cmdhelp
---
## Introduction
When using` docker` we may create a lot of containers, it will be very slow to delete one by one, you can delete all the containers at once by combining commands

This tutorial will teach you how to delete all containers at once

## Command Line
delete all containers
```bash
docker rm $(docker ps -a -q)
```
## Parameter Description
| parameter | Introduction                                                               |
| --------- | -------------------------------------------------------------------------- |
| rm   |Remove one or more containers.|
| ps   |List containers.|
| -a   |Show all containers (default shows just running).|
| -q   |Only display container IDs.|
###  operation result
```
4b67fe5f30b5
cb7d3b455d05
```

### Important reminder
A running container cannot be deleted directly, you need to suspend the container before deleting

#### Notice
If you have any questions in use, you can leave a message below, or submit issuse on github ♥
