# Changelog

All notable changes to this project will be documented in this file.

## Version: 0.3.0

### New features
 - Added config parameter `abi_dir` which allows user to set it and then use not the full path in `abi` options
 - Added subcommand `decode account_messages` which queries and decodes specified amount of inbound messages for the account

### Fixes
 - Fixed SDK callback decoding

## Version: 0.2.0

### Fixes
 - Removed URL form config, now endpoints should be configured directly instead with command `gosh-cli config -e gosh`

## Version: 0.1.1

### Fixes
 - Fixed shutdown after global timeout

## Version: 0.1.0

### Description
Forked [tonos-cli](https://github.com/tonlabs/tonos-cli) to use it on [GOSH](https://app.gosh.sh/)

### Changes
 - Changed th binary name to `gosh-cli`
 - Added shutdown after timeout, which can be configured with `global_timeout` config