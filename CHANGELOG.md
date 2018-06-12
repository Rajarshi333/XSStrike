**Note:** Changes before version 2.0.0 (pre-beta) aren't mentioned and the semantic version naming schema will be followed after a stable release.

#### v2.0.0 (Beta)
- Replaced `alert` with `confirm` in all payloads & functions
- Added new payloads for HULK
- Added detection of GET & POST parameters
- Fixed filter checker
- Fixed some bugs in injector
- Fixed a major bug in WAF detector
- Fixed a bug in parameter finder
- Fixed a bug that generated invalid payloads
- Fixed a bug that caused HULK to inject the same payload everytime
- Added handmade HTML parser
- Fixed JS context injector

#### v2.0.0 (Pre-Beta)
- Intitial Release
- Resolved a bug that caused program to terminate in case of WAF
- Fixed cookie handling