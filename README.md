shared-block-ring
=================

A simple on-disk fixed length queue. This is intended to be used as
the basis of a redo-log mechanism for services which need to be able
to safely restart without losing updates.

Currently it uses complete sectors as slots and stores fixed-length
data, but this should be changed.
