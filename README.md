This tool is no longer maintained. For an active fork please head on over to [zero-motorcycle-community/zero-log-parser](https://github.com/zero-motorcycle-community/zero-log-parser).

---

Little decoder utility to parse Zero Motorcycle main bike board (MBB) ~~and
battery management system (BMS)~~ logs *(note: current version of parser  supports MBB logs only)*. These may be extracted from the bike
using the Zero mobile app. Once paired over bluetooth, select 'Support' >
'Email bike logs' and send the logs to yourself rather than / in addition to
zero support.

Usage:

  `$ python zero_log_parser.py <*.bin file> [-o output_file]`
