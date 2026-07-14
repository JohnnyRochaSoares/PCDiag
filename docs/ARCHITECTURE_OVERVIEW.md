# Architecture Overview

This document describes the high-level architecture concept of PCDiag.

The implementation details may change depending on the selected technology stack.

```
                         PCDiag

                           UI
                           |
                           v
                  Diagnostics Core
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
    Hardware           Software          Network
   Diagnostics        Diagnostics      Diagnostics
          \                |                /
           \               |               /
            +--------------+--------------+
                           |
                           v
             Platform Abstraction Layer
                           |
              +------------+------------+
              |            |            |
           Windows       macOS        Linu

                                    PCDiag

                           UI
                           |
                           v
                  Diagnostics Core
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
    Hardware           Software          Network
   Diagnostics        Diagnostics      Diagnostics
          \                |                /
           \               |               /
            +--------------+--------------+
                           |
                           v
             Platform Abstraction Layer
                           |
              +------------+------------+
              |            |            |
           Windows       macOS        Linuxx
```
