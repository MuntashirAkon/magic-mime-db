# Magic MIME DB

A database of magic (used by unix `file` command) and MIME types (not necessarily the ones set by IANA).

## Motivation

There are a countless number of repositories that provide support for MIME types. But none of them appears to be generic enough to suite my needs, probably because most of them only focused on MIME types alone instead of both magic and MIME types. Although magic does have an option to list MIME types as well as extensions, it is insufficient to rely on it as many MIME types have no magic numbers and are derived MIME types.

## Objectives

The objective of this repository is to provide separate but related databases of magic and MIME types so that developers can easily make use of both. The other objective is to list other non-standard MIME types that are widely used by file managers and other apps.

## Contributing

Magic files are generated automatically from libmagic resources. Therefore, it is highly unlikely that issues regarding them will be solved here. However, any urgent issues might be added.

New MIME types are accepted provided the suggestion contains evidence of the MIME type being used frequently. Most MIME types also have one or more extensions. Sufficient research should be done to include as many supported extensions as one can find. In short, MIME types have the following information:
1. MIME type
2. Name (short and precise)
3. Extensions (if any)
4. Original MIME type (if this MIME type is derived from another MIME type)
5. Source/proof/evidence of use
6. Documentation
7. Full name and contact method (in case the submitted MIME entry has issues).

## Disclaimer

Although sufficient investigations have been carried out for each MIME type, no guarantee is provided regarding the contents of the databases, and the contributors shall not be responsible for any form of damages that may happen due to faulty records. If you find any faulty records, it is recommended that you open a new issue and report it immediately. 

## License

Creative Commons Share Alike 4.0 License (CC-BY-SA-4.0). Scripts and other program files are under GNU General Public License 3.0 or later (GPL-3.0-or-later).

