# Wireshark Dissector Plugin Kit
This project contains definitions/macros/type definitions and libs (for Windows) necessary for building the [dissector](https://www.wireshark.org/docs/wsdg_html_chunked/ChapterDissection.html) out-of-git.
*It lacks a large part of Wireshark API which is not always required.*

## Installation 

The dissector is bundled as a Wireshark plugin, see [Plugin folders](https://www.wireshark.org/docs/wsug_html_chunked/ChPluginFolders.html).

## Notes

A mismatch with the documentation was found, there must be another path for the extension to load correctly:

`{default_path}\Wireshark\plugins\X.X\epan`, where `X.X` version of Wireshark.

## History

The base include header was built by Ivan Djelic <ivan.djelic@parrot.com>, and uses in [libARCommands](https://github.com/Parrot-Developers/libARCommands/tree/master/WiresharkPlugin) project.
