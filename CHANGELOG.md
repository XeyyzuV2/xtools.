# XTOOLS Changelog

All notable changes to XTOOLS will be documented here.

---

## [v2.4] - 2025-12-18

### 🆕 New Features

#### Attack Modules (+8 Modules, Total: 73)
- **blindxss** - Blind XSS payload injection and callback server
- **oauth** - OAuth 2.0 flow vulnerability scanner  
- **ssrfchain** - SSRF chain exploitation with cloud metadata
- **revshell** - Reverse shell generator (multiple languages)
- **dnsrebind** - DNS rebinding attack framework
- **wafbypass** - WAF bypass with payload obfuscation
- **subfuzz** - Subdomain takeover fuzzer
- **zeroday** - Zero-day exploit research assistant

#### Dual-Mode Interface
- **Interactive Menu Mode** - Numbered category selection (original)
- **Command Line Mode** - XTOOLS > prompt with commands:
  - `help` - Show commands
  - `list` - Show all modules
  - `use <module>` - Run a module
  - `info <module>` - Module info
  - `proxy` - Proxy settings
  - `evasion` - Evasion settings
  - `menu` - Switch to interactive mode
  - `exit` - Quit

#### Tier-Specific Animations
- **ROOT**: Crown banner, GOD MODE effects, "Welcome Elite Operator"
- **USER**: VIP diamond banner, module access list
- **GUEST**: Basic banner with upgrade notice

#### Version Check System
- **Mandatory internet connection** - Blocks offline usage
- **Forced update** - Blocks if version < minimum required
- **No skip option** - Users MUST update to continue

#### License System Updates
- **No local cache** - Keys not saved to license.dat (security)
- **In-memory session** - Key stored in RAM during session
- **GUEST key auto-expire** - Free keys deleted 5 minutes after creation
- **HWID mismatch force exit** - Uses os._exit(1) for guaranteed termination

#### Discord Bot Updates
- **!genkey @user [tier] [duration]** - Flexible duration format:
  - `30m` - 30 minutes
  - `12h` - 12 hours  
  - `7d` - 7 days
  - `1y` - 1 year
  - _(none)_ - Lifetime
- Help embed when no arguments provided

---

### 🔧 Bug Fixes

- **License Tier Bug** - Fixed `check_license()` returning boolean instead of dict, causing tier to reset to 'guest'
- **Session Terminated Bug** - Fixed `verify_session()` looking for non-existent license.dat after cache removal
- **Startup Delay** - Reduced API timeout from 5s to 2s, skipped API call in mode selection
- **Proxy/Evasion Status** - Fixed hardcoded "OFF" status, now shows actual state from GlobalConfig
- **HWID Mismatch** - Added proper panel display and force exit with os._exit(1)
- **Red text flash** - Removed tier panel from XTShell init (was flashing before login)

---

### ⚡ Improvements

- Updated all version references to v2.4
- Updated module count to 73 in all displays
- Improved license validation error messages
- Added time.sleep for error visibility
- API documentation updated for new modules and modes

---

### 🔒 Security Enhancements

- License keys no longer saved to disk (in-memory only)
- GUEST keys auto-expire after 5 minutes (prevents hoarding)
- Mandatory version check blocks outdated clients
- HWID mismatch forces immediate program exit

---

## [v2.3] - Previous Version

- check at readme.md
- Single interactive mode
- License caching to license.dat
- Optional version check

---

*For upgrade instructions, visit: https://forum.html-5.me*

