# TankBattle (���克战争) — Upstream: Gitee ayqy/TankBattle

This directory is a copy-import wrapper for the open-source project "TankBattle (坦克战争)" hosted at: https://gitee.com/ayqy/TankBattle

Upstream license: MIT. See LICENSE in this folder for the original authorship and terms.

This folder does not contain the upstream source code by default. To import the upstream source into this repository (as a one-time copy), run the import script below.

## How to import the upstream source

1. Run the script from the repository root (or from this folder):

```bash
chmod +x External/TankBattle/IMPORT_FROM_GITEE.sh
./External/TankBattle/IMPORT_FROM_GITEE.sh
```

2. The script will clone the upstream repo (shallow clone) into `External/TankBattle/src`, remove the .git folder and leave the files in `External/TankBattle/src` so they can be committed into this repository.

3. Inspect files, review license, and then commit the imported files into the current branch.

## Notes
- The upstream project is under the MIT License. Ensure compliance with the license (preserve copyright and license text) when redistributing or modifying.
- If you prefer to include the upstream source including commit history, use git submodule or `git subtree` instead of a direct copy.
