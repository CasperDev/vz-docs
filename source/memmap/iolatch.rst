
IOLATCH
=======

.. _IOLATCH:

Hardware Register (Write Only) directly connected to external devices.

Only 6 bits are used:

  - bit 5 - Speaker Out (-)
  - bit 4 - MC6847 CSS pin - COLOR 0 (Green) or 1 (Orange)
  - bit 3 - MC6847 AG pin - MODE 0 or 1
  - bit 2 - Cassette Out (-) N/C
  - bit 1 - Cassette Out (+)
  - bit 0 - Speaker Out (+)


Speaker Out(+/-)
................

This bits are connected to piezo-speaker. When bit 5 and bit 0 are the same
(0 or 1) there is no voltage beetween plates creates audio line level 0.

