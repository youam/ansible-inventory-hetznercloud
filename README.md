# hetzner_cloud dynamic inventory

## Introduction

Ansible inventories can be provided dynamically by inventory scripts. This
script is an ansible dynamic inventory for the [Hetzner
Cloud](https://console.hetzner.cloud).

## Setup

* Create an account, a project within it and some hosts. You've probably
  already done that, or you wouldn't be here.
* In your project, in `Zugänge`, `API-TOKENS`, create a new api token.
* Get that token into the environment variable `HCLOUD_API_TOKEN`.
* Make the `hetzner_cloud` script executable and put it into your ansible
  inventory. One way to do that is to replace your current static inventory
  file with a directory (probably moving your original inventory into it) and
  put the `hetzner_cloud` script into that directory, too.

## Bugs, Problems, Requests

Please use the github issuetracker.

## License
```
#   hetzner_cloud ansible dynamic inventory
#   Copyright (C) 2018 Uli Martens <uli@youam.net>
# 
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
