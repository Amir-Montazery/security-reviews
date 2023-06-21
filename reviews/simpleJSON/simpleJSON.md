---
Publication-State: Active
Access: Public
Reviewers:
  Organization: Open Source Technology Improvement Fund, Inc
  Associated-With-Project: False
  Compensation-Source: External
Domain: Security
Methodology:
- Static-Analysis
- Dynamic-Analysis
- Code-Review
- Fuzzing
Issues-Identified: Non-Severe
Package-URL(s):
- pkg:simplejson/simplejson
Review-Date: 2023-04-21
Scope: Implementation (Full)
Schema-Version: 1.0
SPDX-License-Identifier: CC-BY-4.0
---

### Summary

OSTIF organized a security audit for simpleJSON.

### Details

OSTIF is pleased to announce that another audit has reached publication! A security audit of simplejson’s source code was conducted in collaboration with X41. 

Found during the audit process were one medium and two low severity issues, as well as nine more informational issues. In addition, custom differential fuzzing harnesses were made to compare C and Python implementations of simplejson with differential fuzzing across simplejson and orjson to ascertain parsing discrepancies in the two libraries. 

X41’s work in the Python encoder/decoder supported previous security research in simplejson. A mature project like simpejson has many maintainers and contributors over its long life, yet there were still minor fissures in the code that were addressed and patched. The efforts provided by a skilled third-party reviewer can help mature projects further their security concerns and goals. 

We thank X41 for their continued work with OSTIF in helping open source projects navigate the complex security space. Also, thank you to Amazon Web Services for sponsoring this critically important work.

### Methodology

No methodology was provided.

### External References

https://ostif.org/our-audit-of-simplejson-is-complete/

### Disclaimer

All security reviews are conducted on a "best-effort" basis against a software
component at a point in time. We make no guarantee as to the quality or completeness
of any review. If you believe any content is inaccurate, we encourage you to open
an issue or submit a pull request with a correction or improvement.

### License

This text is released under at least the
[Creative Commons Attribution 4.0 (CC-BY-4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode.txt).
Externally-referenced content may be licensed differently.
