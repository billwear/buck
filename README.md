# BUCK - Bill's Unix Command Kit
An eclectic collection of command line tools for various and nefarious purposes.

## Personal planner tools (planner)

* abook: prints my address book in /etc
* edcal: edits the default calendar file
* gottados: fetches the active calendar entries tagged with "@gotta"
* jrnlseed: pre-seed today's journal file
* wannados: fetched the active calendar entries tagged with "@wanna".

## Discourse tools (/discourse)

* dcdiff: DisCourse DIFF - diff two discourse directories
* dclock: DisCourse LOCK - lock a discourse topic.
* dcpull: DisCourse PULL - pull a discourse topic.
* dcpush: DisCourse PUSH - push a discourse topic.
* disced.bak: a backup of previous versions of DISCourse EDitor, now being refactored.
* maas_discourse.py: a big (legacy) Discourse API library.
* markdown_py: markdown library of some kind; forgotten what's in it.
* redirect-lint: a tool to lint Discourse redirects, written by @sparkiegeek.
* tab2html: creates HTML from Discourse markdown with embedded [tab] sets.

## LXD (/lxd)

* dhcp-off: turns off DHCP for local LXD
* dhcp-on: turns on DHCP for local LXD
* hack-on: script to build and load a virtual machine for MAAS, written by @sparkiegeek

## Markdown (/markdown)

* dovali: DOcument VAlidator and LInter - general purpose doc post-edit preprocessor.
* json2dctable: creates a Discourse markdown table from JSON output stream.
* mdlint: an early linter; this might be someone else's code.

## General utilities (/utilities)

* fetch: Simple bash script to fetch a URL using lynx dump.
* getwx: fetches the local weather from wttr.in.
* google: Simple bash script to google a topic using lynx dump.
