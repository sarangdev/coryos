[![MIT Licence](https://img.shields.io/badge/license-AGPL--3.0-green)](https://www.gnu.org/licenses/agpl-3.0.en.html)
[![Website](https://img.shields.io/badge/website-click-green)](https://coryos.site)
# CoryOS
A completely fresh "operating system" using [Node.js](https://nodejs.org), written in [TypeScript](https://www.typescriptlang.org) (JS)

# How will it work?
- Lower level:
At the bottom, good old Linux is running. In the future, there are plans to develop own lower level.

- Upper level:
At the top level, we are met by Core, API, coryVM and maitUI.

  - Core
It implements communication with the equipment and connects all the components of the system described earlier.

  - API
A magic thing that allows applications to interact with the system, and in principle-to work.

  - coryVM
And this is more interesting...
This is a "software package" that allows you to run applications of familiar platforms (Windows, Linux, Mac) directly in coryos. A miracle of technology!

  - aitUI
Multifunctional, beautiful, flexible, and most importantly - fast UI for coryOS.
