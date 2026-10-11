# Logging

Configuration Studio page **Logging**. Open it from the left-hand list; type part of a setting's name in the search box to find it.

Which logs GrayDR writes for this character and where. The debug log is the standing diagnosis tool; leave it on.

| Setting | What it does | Default | Applies to |
|---|---|---|---|
| **Normal plain-text log** | Record exactly the visible main-window text without timestamps or formatting. Yes or No. | Yes | Each character |
| **Warning and error snapshots** | Keep a 64 KB recent-text ring and write separate warning/error snapshots. The ring is released when this option is off. Yes or No. | No | Each character |
| **Debug log** | Full timestamped debug capture: everything shown in the window, every command sent with its owner, everything received, and command timing records. The standing diagnosis tool - leave it on. Authentication payloads are redacted. Yes or No. | No | Each character |
| **Log directory** | Leave blank for the shared profile logs directory, or choose another folder. Relative paths are resolved beside engine.yaml. | (blank) | Each character |

