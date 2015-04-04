# dataformat
Each node has an ID.  This facilitates references and multi-view editing.
The raw serialized form is not for manual editing or reading.  It should be 
easy to read/write to JSON/YAML/XML etc.

There should be a text-mode tool for editing and command-line tool to convert from human-readable to non-human readable.

The format is designed to be translated to and from different programming languages.  The primary challenge is maintaining or generating/matching IDs across text editors.
