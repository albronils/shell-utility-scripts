#!/bin/bash
git fetch --all --prune
git branch -vv | grep 'origin/.*: gone]' | awk '{print $1}' | xargs git branch -d
