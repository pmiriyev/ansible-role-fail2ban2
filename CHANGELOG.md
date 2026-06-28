# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.5.0](https://github.com/pmiriyev/ansible-role-fail2ban2/compare/v1.4.2...v1.5.0) (2026-06-28)


### Features

* **fail2ban:** align role with Red Hat CoP standards ([f5f081e](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/f5f081ee201534f6ea8be701f7bbaa6f20b94785))
* **fail2ban:** align role with Red Hat CoP standards ([69aa889](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/69aa8890ea7f7a37dbe71f740c388fb4f45e604c))
* **fail2ban:** improve correctness, robustness, and docs ([ccab18f](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/ccab18ffe94a3679e49f9f2f975127af97060f5f))
* migrate to centralized CI, Release Please, and Galaxy publish ([#3](https://github.com/pmiriyev/ansible-role-fail2ban2/issues/3)) ([8b63bbb](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/8b63bbb9cc5339cb8a16b5baf30fadf321e73858))


### Bug Fixes

* **ci:** upgrade to Node.js 24 actions and standardize enterprise naming ([36f6a76](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/36f6a7623aac54419dee2e4f51ab35ad15a8349c))
* **ci:** upgrade to Node.js 24 actions and standardize enterprise naming ([c2f5553](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/c2f5553d3c2044f691deac5e8811efd6add7eee2))
* **compatibility:** migrate to ansible_facts syntax and fix upgrade logic ([96dd24d](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/96dd24d5b7680f316d0f309b3b72def3c4bf7faa))


### Code Refactoring

* standardize comments, headers, and validations ([#8](https://github.com/pmiriyev/ansible-role-fail2ban2/issues/8)) ([1670ab4](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/1670ab491ff6d26b9c8b947f6a24e2652d30a508))


### Documentation

* add Verification section and standardize H2 emojis in README.md ([#6](https://github.com/pmiriyev/ansible-role-fail2ban2/issues/6)) ([bc5cb4f](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/bc5cb4ffd4ed1798ac9ead5edee2f2475ca044e9))
* Fix workflow filename in README badge 🔧 ([8272a46](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/8272a46c231141f21b18dc36c7d7143c66ccac42))
* Polish documentation, changelog and ensure full lint compliance for fail2ban role ✅ ([cff5506](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/cff55062dbcbe002d9dbea8bdb62dac096a19bcc))
* Update CHANGELOG date to current (2025-07-04) 📅 ([275b467](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/275b467abd0115210a08295066e4baf4799f43b3))


### CI/CD

* align github workflows and gitignore with standard layout ([#5](https://github.com/pmiriyev/ansible-role-fail2ban2/issues/5)) ([8cc57d9](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/8cc57d93da05b30ff1d663b6942cb96f41dce544))


### Miscellaneous

* **fail2ban:** align role with internal Ansible rules; update docs ([09da3cb](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/09da3cb4cb3691d20bc70046e520c515edd23c7c))
* **main:** release 1.4.0 ([#4](https://github.com/pmiriyev/ansible-role-fail2ban2/issues/4)) ([2e547a0](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/2e547a0c228528165b50c8579613c9b17f48792a))
* **main:** release 1.4.1 ([#7](https://github.com/pmiriyev/ansible-role-fail2ban2/issues/7)) ([f095b5b](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/f095b5b7efcd68d0dd585e9879f422a640cb24f2))
* **main:** release 1.4.2 ([#9](https://github.com/pmiriyev/ansible-role-fail2ban2/issues/9)) ([163f1ac](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/163f1ac3f26c332d1306ca32e925dab232a148bb))


### Tests

* Add molecule.yml configuration for Docker-based testing 🧪 ([3d22d18](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/3d22d18d1c5cac4bc0d6011b63c3ec0ea385cce7))
* Add shadow file permission fix to molecule prepare tasks 🔧 ([efb59ab](https://github.com/pmiriyev/ansible-role-fail2ban2/commit/efb59ab15920879d0a97417835712a0ac1d772ad))

## [1.4.2](https://github.com/grzegorzfranus/ansible-role-fail2ban/compare/v1.4.1...v1.4.2) (2026-06-02)


### Code Refactoring

* standardize comments, headers, and validations ([#8](https://github.com/grzegorzfranus/ansible-role-fail2ban/issues/8)) ([1670ab4](https://github.com/grzegorzfranus/ansible-role-fail2ban/commit/1670ab491ff6d26b9c8b947f6a24e2652d30a508))

## [1.4.1](https://github.com/grzegorzfranus/ansible-role-fail2ban/compare/v1.4.0...v1.4.1) (2026-05-24)


### Documentation

* add Verification section and standardize H2 emojis in README.md ([#6](https://github.com/grzegorzfranus/ansible-role-fail2ban/issues/6)) ([bc5cb4f](https://github.com/grzegorzfranus/ansible-role-fail2ban/commit/bc5cb4ffd4ed1798ac9ead5edee2f2475ca044e9))

## [1.4.0](https://github.com/grzegorzfranus/ansible-role-fail2ban/compare/v1.3.0...v1.4.0) (2026-05-24)


### Features

* migrate to centralized CI, Release Please, and Galaxy publish ([#3](https://github.com/grzegorzfranus/ansible-role-fail2ban/issues/3)) ([8b63bbb](https://github.com/grzegorzfranus/ansible-role-fail2ban/commit/8b63bbb9cc5339cb8a16b5baf30fadf321e73858))


### CI/CD

* align github workflows and gitignore with standard layout ([#5](https://github.com/grzegorzfranus/ansible-role-fail2ban/issues/5)) ([8cc57d9](https://github.com/grzegorzfranus/ansible-role-fail2ban/commit/8cc57d93da05b30ff1d663b6942cb96f41dce544))

## [1.3.0] - 2026-05-18

### Added
- Created `meta/argument_specs.yml` for Ansible-native argument validation (CoP §3.1.20)
- Added per-item key validation for `fail2ban_custom_jail_files` entries in assert.yml

### Changed
- Upgraded ansible-lint profile from `min` to `shared` (CoP compliance)
- Refactored `tasks/assert.yml` to runtime-only checks (type/choice validation moved to argument_specs)
- Renamed all internal registered variables to `__fail2ban_` double-underscore prefix (CoP §3.1.4)
- Added `verbosity: 1` to all diagnostic debug tasks (CoP §5.4)
- Converted all `when:` conditions from folded scalar to YAML list format
- Simplified task file headers to single-line comments (Tailscale pattern)
- Removed all emoji characters from task names, assert messages, and debug output
- Updated `min_ansible_version` from `2.15` to `2.16`
- Cleaned up `meta/main.yml` galaxy tags (removed redundant OS-specific entries)

### Fixed
- Removed `meta-no-info` from ansible-lint skip list (meta properly configured)
- README now documents per-task `become: true` instead of recommending global privilege escalation

### Documentation
- Complete README rewrite following Red Hat CoP §3.1.17 and Tailscale reference pattern
- Added Role Properties section (Idempotent, Atomic, Check Mode, Diff Mode)
- Added Role Output section documenting `__fail2ban_` internal fact prefix
- All 37 variables (31 defaults + 6 internal) documented in README tables
- Removed all emoji markers from CHANGELOG section headers

## [1.2.1] - 2026-05-18

### Fixed
- Upgraded `actions/checkout` from v4 to v6 (Node.js 24 compatible)
- Upgraded `actions/setup-python` from v5 to v6 (Node.js 24 compatible)

### Changed
- Standardized workflow and job naming to enterprise convention (Numbered Title Case)

## [1.2.0] - 2025-11-25

### Changed
- Migrated all deprecated `ansible_*` top-level fact variables to `ansible_facts['*']` syntax for Ansible 2.24 compatibility
- Updated `tasks/upgrade.yml`: replaced `ansible_pkg_mgr` with `ansible_facts['pkg_mgr']`
- Updated `tasks/install.yml`: replaced `ansible_distribution_major_version`, `ansible_os_family`, `ansible_pkg_mgr` with `ansible_facts[...]` equivalents
- Updated `tasks/configure.yml`: replaced `ansible_os_family` with `ansible_facts['os_family']`
- Updated `tasks/logrotate.yml`: replaced `ansible_os_family` with `ansible_facts['os_family']`
- Updated `defaults/main.yml`: replaced `ansible_fqdn` with `ansible_facts['fqdn']` in `fail2ban_sender` default
- Updated `molecule/default/prepare.yml`: replaced `ansible_service_mgr`, `ansible_os_family` with `ansible_facts[...]`
- Updated `molecule/default/verify.yml`: replaced `ansible_pkg_mgr`, `ansible_service_mgr` with `ansible_facts[...]`
- Updated `molecule/default/converge.yml`: replaced `ansible_os_family`, `ansible_service_mgr` with `ansible_facts[...]`
- Updated README.md documentation to reflect new variable syntax
- **Breaking:** Upgrade action is now excluded from `all` role action - requires explicit `fail2ban_role_action: 'upgrade'` or `--tags upgrade`
- Added `never` tag to upgrade task to prevent accidental package upgrades during normal role execution

### Fixed
- Resolved Ansible 2.20+ deprecation warnings about `INJECT_FACTS_AS_VARS`
- Role is now fully compatible with upcoming Ansible 2.24 where top-level fact injection will be removed
- Fixed illogical behavior where `fail2ban_role_action: 'all'` would run upgrade immediately after install

## [1.1.0] - 2025-08-11
## [1.1.1] - 2025-09-05

### Changed
- Normalized task and handler names to remove emojis and follow `Rolename | action | description`.
- Updated tags to allowed set: replaced `vars` with `setup, init`; `asserts` with `validate`; removed `custom_jails` tag.
- Converted inline `when:` conditions to folded style where required.
- Documentation updated: tags table reflects allowed tags; variables table verified and aligned with defaults.

### Added
- Assertions for `fail2ban_enable_epel` and for service/package identifiers.
- Assertions ensuring path variables are absolute and defined.

### Fixed
- Consistency between task notify names and handler names.

### Added
- Molecule tuned to test multiple platforms: Rocky 9, Ubuntu 22.04/24.04, Debian 12
- Documentation now lists all variables, including internal service, package, and path variables
- New variable `fail2ban_enable_epel` to control EPEL on EL-family systems
- Configuration validation step using `fail2ban-client -t` before restart

### Changed
- Updated `meta/main.yml` to align supported platforms with `ansible-role-github-runner`
- Switched deprecated `with_items` to `loop` in tasks and Molecule verify playbook
- Replaced shell-based permission step in Molecule `prepare.yml` with `ansible.builtin.file`
- `fail2ban_ignoreself` is now a boolean; templates render `true/false` accordingly
- Service management streamlined: single enable/disable task; restart occurs only when enabled
- Controller-side checks for local custom file paths in configuration deployment
- Systemd override directory permissions set to `0755`

### Fixed
- README supported OS matrix reordered and aligned with meta
- Molecule prepare verified to avoid unnecessary shell usage

## [1.0.2] - 2025-07-04

### Added
- Added molecule.yml configuration file for Docker-based testing
- Enhanced Molecule testing framework with proper Docker platform configuration
- Added support for environment variable-based testing configuration

### Fixed
- Fixed handler name mismatch causing "handler not found" errors
- Fixed task naming convention to use file-based categories instead of module types
- Corrected all task names to follow "Fail2ban | [filename] | [description]" pattern
- Fixed yamllint errors: removed trailing spaces and added newline at end of file
- Achieved 100% compliance with yamllint and ansible-lint standards

## [1.0.1] - 2024-12-19

### Added
- Enhanced task naming with "Fail2ban | category | description" pattern
- Comprehensive validation messages with success/failure indicators
- Enhanced error reporting and debugging capabilities
- Post-installation and post-upgrade verification tasks
- Configuration summary reporting in all task files
- Advanced playbook examples with NFTables integration
- Detailed troubleshooting section with common solutions
- File structure documentation
- Development workflow and testing instructions

### Fixed
- Converted all legacy ansible modules to ansible.builtin format
- Fixed ansible-lint violations (no-handler, package-latest)
- Removed trailing spaces and added missing newlines (yamllint compliance)
- Improved conditional execution patterns consistency
- Enhanced systemd integration with proper handler usage
- Fixed orphaned jail file cleanup logic in custom_jails.yml

### Changed
- ALL task files updated with Ansible best practices
- Improved YAML dictionary format for all module parameters
- Updated handlers with enhanced logging and error handling
- README.md completely redesigned with enhanced formatting and structure
- Consistent tagging strategy across all task files

## [1.0.0] - 2024-03-20

### Added
- Initial release of ansible-role-fail2ban
- Fail2ban package installation and configuration
- Support for Ubuntu 22.04 (Jammy Jellyfish)
- Support for Debian 12 (Bookworm)
- Support for Rocky Linux 9 and EL 9
- Custom jail configuration support
- Email notification configuration
- Progressive ban time features (bantime.increment)
- Logrotate configuration for fail2ban logs
- nftables and iptables backend support
- Custom filters for OpenVPN and FreeIPA GUI
- Comprehensive variable validation
- Systemd service integration
- Role action control (install, configure, upgrade, etc.)
