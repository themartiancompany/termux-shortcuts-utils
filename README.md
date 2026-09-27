[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)


# Termux Shortcuts Utilities (`termux-shortcuts-utils`)

Utilities to manage
[Termux shortcuts](
  https://github.com/termux/termux-widget).
Actually one.

- `termux-shortcut-new`:
     creates a termux shortcut from
     a [freedesktop desktop file](
         https://specifications.freedesktop.org/desktop-entry-spec/1.1).

## Usage

Help can be displayed by typing

```bash
termux-shortcut-new \
  -h
```

further informations are made available in
the manual.

```bash
man \
  termux-shortcut-new
```

## Installation

The utilities in this source repo
can be installed from source using GNU Make.

```bash
make \
  install
```

The utilities have officially been published on the
the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`termux-shortcuts-utils`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  termux-shortcuts-utils
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[termux-shortcuts-utils-ur](
  https://github.com/themartiancompany/termux-shortcuts-utils-ur).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

Newer versions of Videogame Launcher are exclusively sold on the
Ur. The software stays licensed under a copyleft license.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
