#!/usr/bin/env bash
set -e

cd ~/forge

git add .
git commit -m "vault backup: $(date '+%Y-%m-%d %H:%M')" || true
git push origin main