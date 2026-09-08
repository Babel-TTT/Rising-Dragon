# Military Pack - README

1. General Information
2. Building
3. Credits
4. License

## 1. General Information

Military Pack is an OpenTTD road-vehicle set featuring military vehicles.
It is licensed under GPL v2.

**Status: work in progress.** The repository currently contains only the GRF
skeleton (build system, language files and source layout); no vehicles have
been added yet. The project structure intentionally mirrors
[China-Set-Buses](https://github.com/OpenTTD-China-Set/China-Set-Buses) so that
vehicles can be added one file at a time under `src/`.

Planned content (subject to change):
- military trucks, jeeps and other support vehicles

## 2. Building

The source is available on GitHub. These tools are required to build the GRF:

- nml
- make
- gcc
- (gorender, or renderobject — only needed once voxel models are added under `gfx/`)

Using Linux or WSL:

```bash
#!/bin/bash
# dependencies
sudo apt install make
pip3 install nml
# we would also need gcc, but that should be already included in most distros

# compiling
make
```

Using Windows (Scoop is advised here, but non-scoop compilations are also possible):

```powershell
# dependencies
scoop bucket add main
scoop bucket add openttd https://github.com/WenSimEHRP/OpenTTD-Bucket
scoop install python
scoop install make
scoop install openttd/nml
scoop install mingw

# compiling
make
```

## 3. Credits

Contributors (in alphabetical order):

- (to be filled in)

## 4. License

Military Pack

Copyright (C) 2026 Military Pack Team

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, please check
https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html
