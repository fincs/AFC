AutoHotkey Foundation Classes v0.1
----------------------------------

AFC is a thin object-oriented wrapper around some of AutoHotkey's functionality.
It mainly takes care of wrapping long-time present commands and functions that
use old and quirky paradigms into a saner and cleaner class-based API.

AFC is designed to be modular, and to be as direct as possible with the original
API. This translates to not having otherwise obvious properties that are implemented
through flexi-lists. The author believes that the performance and code size penalty
is not justified.

AFC provides:

* Structured class-based entry points.
* GUI API
* Default base object, which provides OOP syntax sugar for non-object values (such as `str.Length`)

AFC will provide in the future:

* Menus
* Timers
* Hotkeys and hotstrings (perhaps?)
