# Changelog

All notable changes to PElevate are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Fixed
- Auto-detect of the calling batch file now works on Windows 11 and systems without `wmic`
  (uses PowerShell `Get-CimInstance` to read the parent `cmd.exe` command line).

## [1.0] - 2025-01-15

### Added
- Initial public release
- Run batch files with administrator privileges (UAC elevation)
- Pass arguments to the elevated batch file
