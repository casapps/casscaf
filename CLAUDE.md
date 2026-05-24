```
Default Configuration: Port 3000, high-performance runtime with built-in bundler
Features: Extremely fast runtime, built-in bundler, package manager, test runner, Node.js compatibility

MOBILE DEVELOPMENT FRAMEWORKS:

React Native Framework Template:
Dependencies: react-native@0.72.7, react@18.2.0, expo@^49.0.0, react-navigation@^6.0.0
Development Dependencies: @types/react@18.2.45, @types/react-native@0.72.6, jest@29.7.0, detox@20.13.5
Default Configuration: Expo managed workflow, component-based architecture
Project Structure: Component-based with screens, components, navigation, services
Features: Hot reload, over-the-air updates, native module access, cross-platform development

Flutter Framework Template:
Dependencies: Flutter SDK with Dart, material design packages, cupertino widgets
Development Dependencies: flutter_test, integration_test, flutter_driver
Default Configuration: Material Design and Cupertino widgets, hot reload
Project Structure: Widget-based architecture with screens, widgets, models, services
Features: Hot reload, native performance, widget-based UI, cross-platform with single codebase

Ionic Framework Template:
Dependencies: @ionic/angular@7.5.6, @capacitor/core@5.5.1, @capacitor/ios@5.5.1, @capacitor/android@5.5.1
Development Dependencies: @ionic/cli@7.2.0, @capacitor/cli@5.5.1
Default Configuration: Hybrid mobile development with web technologies
Project Structure: Page-based architecture with services, components, providers
Features: Web-based mobile apps, native device access via Capacitor, cross-platform development

DESKTOP DEVELOPMENT FRAMEWORKS:

Electron Framework Template:
Dependencies: electron@27.1.3, electron-builder@24.8.0
Development Dependencies: @types/node@20.10.5, typescript@5.3.3
Default Configuration: Multi-process architecture with main and renderer processes
Project Structure: Main process, renderer process, preload scripts, IPC communication
Features: Web technologies for desktop, native OS integration, auto-updater, system tray

Tauri Framework Template:
Dependencies: tauri@1.5.4, serde@1.0.195, tokio@1.35.1
Frontend Dependencies: Configurable (React, Vue, Svelte, or vanilla)
Default Configuration: Rust backend with web frontend
Project Structure: Rust backend (src-tauri), web frontend (src), IPC bridge
Features: Smaller bundle size, better security, native performance, web frontend flexibility

STATIC SITE GENERATORS:

Hugo Framework Template:
Dependencies: Hugo binary (Go-based static site generator)
Default Configuration: Fast build times, theme system, content management
Project Structure: content/, layouts/, static/, themes/, config files
Features: Extremely fast builds, theme system, shortcodes, multilingual support

Astro Framework Template:
Dependencies: astro@4.0.6, framework adapters (React, Vue, Svelte optional)
Development Dependencies: @astrojs/check@0.3.3, typescript@5.3.3
Default Configuration: Component islands architecture, selective hydration
Project Structure: Pages, components, layouts with framework-agnostic approach
Features: Component islands, zero-JS by default, framework flexibility, optimized performance

COMPREHENSIVE TEMPLATE SYSTEM IMPLEMENTATION:

Template Engine Configuration:
Primary Engine: Handlebars@4.5.0 with custom helper functions
Template Compression: ZSTD level 3 compression with 64KB dictionary
Template Storage: Embedded in binary with lazy decompression
Template Validation: Compile-time validation of all templates with test contexts

HANDLEBARS CUSTOM HELPERS COMPLETE SPECIFICATION:

String Manipulation Helpers:
capitalize(input: string) -> string: Capitalizes first letter ("hello world" -> "Hello world")
uppercase(input: string) -> string: Converts to uppercase ("hello" -> "HELLO")
lowercase(input: string) -> string: Converts to lowercase ("HELLO" -> "hello")
trim(input: string) -> string: Removes leading and trailing whitespace
trim_start(input: string) -> string: Removes leading whitespace only
trim_end(input: string) -> string: Removes trailing whitespace only
split(input: string, delimiter: string) -> array: Splits string by delimiter
join(array: array, delimiter: string) -> string: Joins array elements with delimiter
replace(input: string, pattern: string, replacement: string) -> string: Replaces pattern with replacement
substring(input: string, start: number, length?: number) -> string: Extracts substring
truncate(input: string, length: number, suffix?: string) -> string: Truncates with optional suffix

Case Conversion Helpers:
snake_case(input: string) -> string: Converts to snake_case ("HelloWorld" -> "hello_world")
kebab_case(input: string) -> string: Converts to kebab-case ("HelloWorld" -> "hello-world")
camel_case(input: string) -> string: Converts to camelCase ("hello_world" -> "helloWorld")
pascal_case(input: string) -> string: Converts to PascalCase ("hello_world" -> "HelloWorld")
constant_case(input: string) -> string: Converts to CONSTANT_CASE ("hello_world" -> "HELLO_WORLD")
title_case(input: string) -> string: Converts to Title Case ("hello world" -> "Hello World")

Pluralization and Humanization Helpers:
pluralize(input: string) -> string: Converts singular to plural form
singularize(input: string) -> string: Converts plural to singular form
ordinalize(input: number) -> string: Converts number to ordinal (1 -> "1st", 2 -> "2nd")
humanize(input: string) -> string: Converts technical names to human-readable

Conditional Logic Helpers:
eq(a: any, b: any) -> boolean: Equality comparison
ne(a: any, b: any) -> boolean: Not equal comparison
gt(a: number, b: number) -> boolean: Greater than comparison
lt(a: number, b: number) -> boolean: Less than comparison
gte(a: number, b: number) -> boolean: Greater than or equal comparison
lte(a: number, b: number) -> boolean: Less than or equal comparison
and(a: any, b: any) -> boolean: Logical AND operation
or(a: any, b: any) -> boolean: Logical OR operation
not(input: any) -> boolean: Logical NOT operation
if_any(array: array) -> boolean: Returns true if any element is truthy
if_all(array: array) -> boolean: Returns true if all elements are truthy

Array and Collection Helpers:
first(array: array) -> any: Returns first element
last(array: array) -> any: Returns last element
nth(array: array, index: number) -> any: Returns nth element (0-indexed)
length(input: array | string) -> number: Returns length of array or string
sort(array: array, key?: string) -> array: Sorts array optionally by object key
reverse(array: array) -> array: Reverses array order
unique(array: array) -> array: Removes duplicate elements
filter(array: array, predicate: string) -> array: Filters elements by predicate
map(array: array, transform: string) -> array: Transforms elements
find(array: array, predicate: string) -> any: Finds first matching element
group_by(array: array, key: string) -> object: Groups array elements by key

Date and Time Helpers:
now() -> string: Current timestamp in ISO format ("2024-01-15T10:30:45Z")
format_date(format: string) -> string: Formats current date with pattern
year() -> string: Current year ("2024")
month() -> string: Current month ("01")
day() -> string: Current day ("15")
timestamp() -> number: Unix timestamp
relative_time(date: string) -> string: Human-readable relative time ("2 hours ago")
add_time(date: string, duration: string) -> string: Adds duration to date
subtract_time(date: string, duration: string) -> string: Subtracts duration from date

Encoding and Security Helpers:
base64_encode(input: string) -> string: Base64 encoding
base64_decode(input: string) -> string: Base64 decoding
url_encode(input: string) -> string: URL encoding
url_decode(input: string) -> string: URL decoding
html_escape(input: string) -> string: HTML entity escaping
json_escape(input: string) -> string: JSON string escaping
shell_escape(input: string) -> string: Shell argument escaping
sql_escape(input: string) -> string: SQL injection prevention escaping

Cryptographic Helpers:
sha256(input: string) -> string: SHA-256 hash
sha1(input: string) -> string: SHA-1 hash
md5(input: string) -> string: MD5 hash
blake3(input: string) -> string: BLAKE3 hash
uuid_v4() -> string: Generate UUID v4
random_string(length: number) -> string: Generate random string
random_number(min: number, max: number) -> number: Generate random number
random_choice(array: array) -> any: Choose random element from array

File System Helpers (Security Restricted):
read_file(path: string) -> string: Read file content (restricted to project directory)
file_exists(path: string) -> boolean: Check if file exists
directory_exists(path: string) -> boolean: Check if directory exists
relative_path(from: string, to: string) -> string: Calculate relative path
absolute_path(path: string) -> string: Convert to absolute path
path_join(segments: array) -> string: Join path segments
path_dirname(path: string) -> string: Get directory name
path_basename(path: string) -> string: Get base filename
path_extension(path: string) -> string: Get file extension

Environment and System Helpers:
env_var(name: string, fallback?: string) -> string: Get environment variable with optional fallback
has_env(name: string) -> boolean: Check if environment variable exists
platform() -> string: Current platform ("linux", "macos", "windows")
arch() -> string: Current architecture ("x86_64", "aarch64")
current_dir() -> string: Current working directory

TEMPLATE CONTEXT STRUCTURE COMPLETE:
Every template receives comprehensive context with all necessary variables:

Project Metadata Context:
project_name: Original project name as entered by user
project_name_snake: snake_case version (my-awesome-app -> my_awesome_app)
project_name_kebab: kebab-case version (MyAwesomeApp -> my-awesome-app)
project_name_camel: camelCase version (my-awesome-app -> myAwesomeApp)
project_name_pascal: PascalCase version (my-awesome-app -> MyAwesomeApp)
project_name_constant: CONSTANT_CASE version (my-awesome-app -> MY_AWESOME_APP)
description: Project description from user input or default
version: Initial project version (default: "0.1.0")
license: License type (default: "MIT")

Author Information Context:
author_name: Author full name from git config or prompt
author_email: Author email from git config or prompt
author_url: Author URL/website (optional)
author_github: GitHub username (derived from git remote or prompt)

Repository Information Context:
repo_url: Full repository URL
repo_platform: git platform ("github", "gitlab", "bitbucket")
repo_owner: Repository owner/organization name
repo_name: Repository name
repo_ssh_url: SSH clone URL
repo_https_url: HTTPS clone URL

Language and Framework Context:
language_name: Programming language ("node", "python", "go", "rust", etc.)
language_version: Specific version being used ("20.10.0", "3.12.1", etc.)
language_ecosystem: Ecosystem identifier for templates
framework_name: Framework being used ("express", "fastapi", "gin", etc.)
framework_version: Framework version
framework_type: Type classification ("backend", "frontend", "fullstack", "cli", "library")

Feature Flags Context:
features_auth: Boolean for authentication features
features_database: Boolean for database integration
features_docs: Boolean for documentation generation
features_docker: Boolean for Docker containerization
features_ci: Boolean for CI/CD pipeline generation
features_testing: Boolean for test framework inclusion
features_linting: Boolean for code linting setup
features_formatting: Boolean for code formatting setup
features_monitoring: Boolean for monitoring/observability
features_logging: Boolean for structured logging

API Configuration Context:
api_version: API version (default: "v1")
api_prefix: API route prefix (default: "/api")
api_port: Server port (framework-specific defaults)
api_host: Server host (default: "localhost" or "0.0.0.0")
api_base_url: Complete base URL for API
api_cors_enabled: CORS configuration flag
api_rate_limiting: Rate limiting configuration flag

Database Configuration Context:
db_provider: Database provider ("postgresql", "mysql", "sqlite", "mongodb", "redis")
db_name: Database name (derived from project name)
db_host: Database host (default: "localhost")
db_port: Database port (provider-specific defaults)
db_username: Database username (default: project name)
db_ssl: SSL configuration flag
db_pool_size: Connection pool size

Authentication Configuration Context:
auth_provider: Authentication provider ("jwt", "oauth2", "session", "passport")
auth_secret_key: Secret key for signing (generated)
auth_expiration: Token expiration time
auth_issuer: JWT issuer
auth_audience: JWT audience
auth_refresh_tokens: Refresh token support flag

Environment Context:
env_development: Development environment configuration
env_production: Production environment configuration
env_testing: Testing environment configuration
current_env: Current environment being generated for

Platform and System Context:
target_os: Target operating system ("linux", "macos", "windows")
target_arch: Target architecture ("x86_64", "aarch64")
build_distro: Linux distribution if applicable
build_tools: Available build tools

Timestamp Context:
created_at: Project creation timestamp (ISO format)
year: Current year
month: Current month
day: Current day
timestamp: Unix timestamp

Dependencies Context:
dependencies: Array of runtime dependencies with versions
dev_dependencies: Array of development dependencies with versions
optional_dependencies: Array of optional dependencies

Generated Components Context:
routes: Array of generated API routes
models: Array of generated data models
services: Array of generated service classes
middlewares: Array of generated middleware components
tests: Array of generated test files

Custom Variables Context (Extensible):
custom: Object containing any additional variables specific to templates or user input

LANGUAGE VERSION MANAGEMENT SYSTEM COMPLETE:

Version Storage Architecture Detailed:
Base Directory: Data directory + "/versions/" + language name
Version Structure: Each version in separate directory (e.g., "20.10.0/", "3.12.1/")
Directory Contents: Complete language installation with bin/, lib/, include/, share/ subdirectories
Current Symlink: "current" symlink pointing to active version
Global Default: Stored in configuration as fallback
Project Local: Version files (.node-version, .python-version, etc.) take precedence

Version Resolution Algorithm Implementation:
1. Project-local version files (.node-version, .python-version, .go-version, rust-toolchain.toml, .ruby-version, .java-version, .php-version)
2. Directory traversal up tree looking for version files (up to filesystem root)
3. Environment variables (NODE_VERSION, PYTHON_VERSION, etc.)
4. Global configuration default from global.toml
5. Current symlink if exists
6. Latest installed version discovered
7. System installation fallback if available
8. Download and install latest stable if none found

Shim System Implementation:
Location: Data directory + "/bin/"
Unix Shim Template (chmod +x):
```bash
#!/bin/bash
# CASSCAF shim for {executable}
CASSCAF_ROOT="{casscaf_data_dir}"
VERSION_DIR="$CASSCAF_ROOT/versions/{language}/current"
EXECUTABLE="$VERSION_DIR/bin/{executable}"

if [ -x "$EXECUTABLE" ]; then
    exec "$EXECUTABLE" "$@"
else
    echo "Error: {executable} not found. Install with: casscaf install {language}" >&2
    exit 1
fi
```

Windows Shim Template (batch file):
```batch
@echo off
REM CASSCAF shim for {executable}
set CASSCAF_ROOT={casscaf_data_dir}
set VERSION_DIR=%CASSCAF_ROOT%\versions\{language}\current
set EXECUTABLE=%VERSION_DIR%\bin\{executable}.exe

if exist "%EXECUTABLE%" (
    "%EXECUTABLE%" %*
) else (
    echo Error: {executable} not found. Install with: casscaf install {language} >&2
    exit /b 1
)
```

Version Installation Methods by Language:

Node.js Installation:
Method: Binary download from nodejs.org
Source URL: https://nodejs.org/dist/v{version}/node-v{version}-{platform}-{arch}.tar.xz
Verification: SHA-256 checksum validation
Extraction: tar.xz archive to versions/node/{version}/
Shims Created: node, npm, npx, corepack
Post-Install: Update current symlink, rebuild shims

Python Installation:
Method: Source compilation with full module support
Source URL: https://www.python.org/ftp/python/{version}/Python-{version}.tar.xz
Dependencies: libssl-dev, libsqlite3-dev, libncurses5-dev, libgdbm-dev, libbz2-dev, liblzma-dev, libreadline-dev, libffi-dev
Configure: ./configure --prefix={install_dir} --enable-optimizations --with-lto --enable-shared
Compilation: make -j{cpu_cores} && make install
Modules: ssl, sqlite3, tkinter, curses, readline, zlib, bz2, lzma, ctypes, decimal, json, urllib, http, socket
Shims Created: python, python3, pip, pip3
Post-Install: Install/upgrade pip, setuptools, wheel

Go Installation:
Method: Binary download from golang.org
Source URL: https://golang.org/dl/go{version}.{platform}-{arch}.tar.gz
Verification: SHA-256 checksum validation
Extraction: tar.gz archive to versions/go/{version}/
Environment: GOROOT set to installation directory, GOPATH managed separately
Shims Created: go, gofmt, godoc
Post-Install: Update current symlink, rebuild shims

Rust Installation:
Method: rustup integration or binary download
Primary: Use existing rustup if available with `rustup install {version}`
Fallback: Binary download from GitHub releases
Components: rustc, cargo, clippy, rustfmt, rust-src, rust-docs, rust-analyzer
Shims Created: rustc, cargo, clippy, rustfmt, rust-analyzer
Post-Install: Update current symlink, install common tools

PHP Installation:
Method: Source compilation with extensions
Source URL: https://www.php.net/distributions/php-{version}.tar.xz
Dependencies: libssl-dev, libcurl4-openssl-dev, libxml2-dev, libgd-dev, libmysqlclient-dev, libpq-dev, libsqlite3-dev
Configure: ./configure --prefix={install_dir} --enable-fpm --with-curl --with-openssl --enable-mbstring --with-gd --enable-intl --enable-zip --with-zlib --enable-soap --enable-bcmath
Extensions: curl, openssl, gd, imagick, mysqli, pdo-mysql, pdo-pgsql, pdo-sqlite, redis, opcache, xdebug, memcached, yaml, zip, bcmath, intl, soap, xmlrpc, mbstring
Shims Created: php, php-fpm, composer
Post-Install: Install Composer globally

Ruby Installation:
Method: Source compilation with ecosystem support
Source URL: https://cache.ruby-lang.org/pub/ruby/{major}.{minor}/ruby-{version}.tar.xz
Dependencies: libssl-dev, libreadline-dev, zlib1g-dev, libyaml-dev, libgmp-dev
Configure: ./configure --prefix={install_dir} --enable-shared --with-jemalloc
Features: openssl, readline, yaml, gmp, jemalloc memory allocator
Jekyll Support: Complete GitHub Pages gem ecosystem compilation
Shims Created: ruby, gem, bundler, rake, irb
Post-Install: Install bundler, update RubyGems

Java Installation:
Method: Binary download from OpenJDK distributions
Sources: Adoptium Eclipse Temurin, Oracle OpenJDK, Amazon Corretto
URL Pattern: https://api.adoptium.net/v3/binary/latest/{version}/ga/{platform}/{arch}/jdk/hotspot/normal/adoptium
Verification: SHA-256 checksum validation
Extraction: tar.gz or zip archive to versions/java/{version}/
Environment: JAVA_HOME set to installation directory
Shims Created: java, javac, jar, jshell
Post-Install: Install Maven and/or Gradle

Latest Version Resolution with Caching:
Cache Duration: 1 hour TTL for API responses
Node.js: Query https://nodejs.org/dist/index.json, parse for latest LTS and Current
Python: Query https://api.github.com/repos/python/cpython/releases, parse release tags
Go: Query https://golang.org/VERSION?m=text for latest version
Rust: Query https://api.github.com/repos/rust-lang/rust/releases for stable/beta/nightly
PHP: Query https://www.php.net/releases/active for active versions
Ruby: Query https://api.github.com/repos/ruby/ruby/releases for latest stable
Java: Query Adoptium API for available LTS and feature releases

Development Channel Support:
Channel Priority for "dev" command: nightly > beta > rc > alpha (first available)
Channel Priority for "beta" command: beta > rc > alpha (exclude nightly)
Specific Channels: Allow exact channel specification (nightly, beta, alpha, rc)
Warning System: Clear instability warnings for development versions
Confirmation: Require user confirmation for non-stable installations

CROSS-PLATFORM BUILD SYSTEM DETAILED:

Linux Build Support Complete:
Distribution Detection: /etc/os-release parsing with fallback to lsb_release
Supported Distributions: Ubuntu, Debian, Fedora, CentOS, RHEL, Arch Linux, Alpine, OpenSUSE, Gentoo, Void Linux, NixOS
Package Manager Mapping:
- apt (Debian/Ubuntu): sudo apt update && sudo apt install -y
- dnf (Fedora/RHEL 8+): sudo dnf install -y
- yum (CentOS 7/RHEL 7): sudo yum install -y
- pacman (Arch): sudo pacman -S --noconfirm
- zypper (openSUSE): sudo zypper install -y
- apk (Alpine): sudo apk add
- portage (Gentoo): sudo emerge
- xbps (Void): sudo xbps-install -y
- nix (NixOS): nix-env -i

Dependency Mapping Tables:
build_essential: build-essential (apt), @development-tools (dnf), base-devel (pacman), patterns-devel-base-devel_basis (zypper), build-base (apk)
ssl_dev: libssl-dev (apt), openssl-devel (dnf), openssl (pacman), openssl-dev (apk)
python_dev: python3-dev python3-pip (apt), python3-devel python3-pip (dnf), python python-pip (pacman)
xml_dev: libxml2-dev (apt), libxml2-devel (dnf), libxml2 (pacman)

macOS Build Support Complete:
Xcode Detection: xcode-select --print-path validation
Command Line Tools: xcode-select --install if missing
Homebrew Integration: brew install for dependencies
Framework Support: Core Foundation, Security, System Configuration frameworks
Universal Binary: Build for both Intel and Apple Silicon when applicable
Dependency Mapping:
build_essential: Xcode Command Line Tools
ssl_dev: openssl (homebrew)
python_dev: python@3.12 (homebrew)

Windows Build Support Complete:
Build Tools Detection: Visual Studio Build Tools, MinGW-w64, MSYS2
MSVC Integration: vcvarsall.bat sourcing for environment setup
Compiler Toolchain: Visual Studio Build Tools 2022 (free download)
Environment Setup: PATH, INCLUDE, LIB variables configuration
Dependency Mapping:
build_essential: Microsoft.VisualStudio.2022.BuildTools (winget), "C++ build tools" workload
ssl_dev: Pre-built OpenSSL libraries or vcpkg
python_dev: python (winget/chocolatey)

Privilege Management Strategy:
Detection: sudo -n true for passwordless sudo (Linux/macOS), token check (Windows)
User Communication: Clear explanations before any privilege escalation
Selective Escalation: Only for operations that actually require privileges
Time-Limited: Drop privileges immediately after operations
Graceful Degradation: Continue with user-space installation if privileges unavailable
Manual Instructions: Provide copy-pasteable commands for manual execution

BACKGROUND TASK SCHEDULING SYSTEM COMPLETE:

Task Queue Architecture:
Queue Implementation: Priority queue with FIFO ordering per priority level
Persistence: JSON serialization in runtime directory for crash recovery
Worker Pool: CPU cores / 2 workers by default (configurable 1-16)
Priority Levels: 0 (user-initiated), 1 (system maintenance), 2 (background downloads), 3 (optimization)
Resource Limits: CPU threshold 80%, memory threshold 80%, configurable

Task Types with Specifications:
Language Compilation Tasks:
- Source download and verification
- Dependency installation and validation
- Configure script execution with optimal flags
- Parallel compilation using all available CPU cores
- Installation to target directory
- Shim generation and PATH integration
- Verification and testing of installation

Binary Download Tasks:
- HTTP download with resume capability
- SHA-256 checksum verification
- Progress tracking with ETA calculation
- Extraction to target directory
- Permission setting and validation

System Dependency Installation:
- Package manager detection
- Privilege requirement evaluation
- Batch installation for efficiency
- Verification of installed packages
- Error handling and retry logic

Cache Cleanup Tasks:
- Old download cleanup (>30 days)
- Temporary file removal
- Log file rotation
- Disk space monitoring
- Cache size optimization

Version Update Tasks:
- API polling for new releases
- Version comparison and filtering
- Background preparation for updates
- User notification of available updates

Resource Management Implementation:
CPU Monitoring: /proc/loadavg (Linux), system APIs (macOS/Windows)
Memory Monitoring: /proc/meminfo (Linux), system APIs (macOS/Windows)
Disk Space: statvfs/GetDiskFreeSpace APIs
Battery Detection: Power source monitoring, GPU acceleration disabling on battery
I/O Throttling: Batch disk operations, avoid disk thrashing

Progress Tracking System:
Real-time Updates: WebSocket/IPC for live progress updates
Stage Tracking: Download, extract, configure, compile, install, verify stages
ETA Calculation: Historical build times for same language/platform combination
Resource Usage: CPU, memory, disk usage display
Completion Statistics: Success/failure rates, performance metrics

User Interface Integration:
Status Bar: Active job count and current operation indicator
Progress Windows: Detailed progress with per-job status, log streaming, controls
Notifications: Native OS notifications for completion/errors
Job Controls: Pause, cancel, retry operations
Queue Management: Reorder, prioritize, remove jobs

CROSS-PLATFORM PACKAGE MANAGEMENT INTEGRATION COMPLETE:

Linux Package Manager Detection Algorithm:
1. Check for apt: command -v apt && test -f /etc/debian_version
2. Check for dnf: command -v dnf && test -f /etc/redhat-release
3. Check for yum: command -v yum && test -f /etc/redhat-release && ! command -v dnf
4. Check for pacman: command -v pacman && test -f /etc/arch-release
5. Check for zypper: command -v zypper && test -f /etc/SuSE-release
6. Check for apk: command -v apk && test -f /etc/alpine-release
7. Check for emerge: command -v emerge && test -d /usr/portage
8. Check for xbps-install: command -v xbps-install && test -f /etc/void-release

Package Installation Command Templates:
apt: sudo apt update && sudo apt install -y {packages}
dnf: sudo dnf install -y {packages}
yum: sudo yum install -y {packages}
pacman: sudo pacman -S --noconfirm {packages}
zypper: sudo zypper install -y {packages}
apk: sudo apk add {packages}
emerge: sudo emerge {packages}
xbps-install: sudo xbps-install -y {packages}

macOS Package Manager Support:
Homebrew: brew install {packages} (primary)
MacPorts: sudo port install {packages} (secondary)
Detection: command -v brew || command -v port

Windows Package Manager Support:
winget: winget install --accept-package-agreements {packages} (primary)
Chocolatey: choco install -y {packages} (secondary)
Scoop: scoop install {packages} (tertiary)
Detection: command -v winget || command -v choco || command -v scoop

Dependency Resolution Strategy:
Missing Package Detection: Test compilation with minimal program
Installation Orchestration: Batch related dependencies together
User Confirmation: Clear explanation of packages being installed
Fallback Instructions: Manual installation commands if automatic fails
Error Recovery: Detailed error messages with resolution steps

SUDO DETECTION AND CACHING SYSTEM COMPLETE:

Sudo Testing Implementation:
Silent Test: sudo -n true >/dev/null 2>&1 (no password prompt)
Cache Duration: 2 minutes (120 seconds) for successful authentication
Cache Location: Runtime directory + "/sudo_cache.json"
CI/CD Detection: Environment variables CI, CONTINUOUS_INTEGRATION, GITHUB_ACTIONS, etc.

CI/CD Environment Variables:
CI, CONTINUOUS_INTEGRATION, GITHUB_ACTIONS, GITLAB_CI, JENKINS_URL, BUILDKITE, CIRCLECI, TRAVIS, AZURE_PIPELINES, TEAMCITY_VERSION, BAMBOO_BUILDKEY, DRONE, CODEBUILD_BUILD_ID
Additional Indicators: !isatty(stdin), username patterns (jenkins, runner, build, ci), container environment

Cache Structure:
```json
{
  "state": "Available|AvailableWithPassword|Unavailable",
  "timestamp": 1704067200,
  "expires_at": 1704067320,
  "password_required": false,
  "test_count": 5,
  "last_success": 1704067200
}
```

Installation Strategy by Sudo Availability:
If passwordless sudo available:
- Install to system directories (/usr/local/share/casscaf/, /usr/local/bin/)
- Shared by all users on system
- Automatic PATH integration
- System-wide package dependency installation

If no sudo available:
- Install to user directories (~/.local/share/casscaf/, ~/.local/share/casscaf/bin/)
- User-specific installation
- Manual PATH setup required
- Graceful degradation with helpful instructions

Password Prompt Implementation (Non-CI Only):
GUI: Native OS dialogs (pkexec, osascript, UAC)
TUI: Custom secure password input widget
CLI: Standard sudo password prompt
Timeout: 30 seconds for password entry
Security: No password storage, immediate memory clearing

ERROR HANDLING AND RECOVERY SYSTEM COMPLETE:

Error Categories and Codes:
1000-1999: User Input Errors
- 1001: Invalid project name format
- 1002: Invalid language version specification
- 1003: Invalid framework selection
- 1004: Invalid configuration values

2000-2999: System Errors
- 2001: Insufficient permissions for operation
- 2002: Insufficient disk space for installation
- 2003: Network timeout or connectivity issues
- 2004: System dependencies missing

3000-3999: Installation Errors
- 3001: Language version not found or unavailable
- 3002: Compilation failed with build errors
- 3003: System dependency installation failed
- 3004: Downloaded file corruption or verification failure

4000-4999: Template Errors
- 4001: Template not found for language/framework combination
- 4002: Template corruption or parsing failure
- 4003: Template rendering failed with context errors
- 4004: Template validation failed

Error Message Design Principles:
Clear Problem Identification: Specific error description without technical jargon
Actionable Solutions: Copy-pasteable commands for resolution
Context Information: Relevant system/environment details
Escalation Path: Support resources when automated solutions unavailable
Recovery Suggestions: Alternative approaches when primary method fails

Error Recovery Strategies:
Graceful Degradation: Continue operation with reduced functionality when possible
Automatic Retry: Exponential backoff for transient failures (1s, 2s, 4s, max 3 retries)
User Guidance: Step-by-step resolution instructions
Rollback Capability: Undo partially completed operations that fail
Diagnostic Information: Log collection and system state capture

SHELL INTEGRATION VIA EVAL COMMAND COMPLETE:

Shell Detection Algorithm:
1. Check parent process name from $0 environment variable
2. Fallback to $SHELL environment variable parsing
3. Platform-specific detection for Windows (PowerShell vs CMD)
4. Default to bash for unknown shells

Shell Integration Commands:
casscaf shell: Auto-detect current shell and output appropriate integration code
casscaf shell bash: Explicit bash integration
casscaf shell zsh: Explicit zsh integration  
casscaf shell fish: Explicit fish integration
casscaf shell powershell: Explicit PowerShell integration

Bash/Zsh Integration Output:
```bash
export PATH="$HOME/.local/share/casscaf/bin:$PATH"

_casscaf_completion() {
    local cur prev opts
    COMPREPLY=()
    cur="${COMP_WORDS[COMP_CWORD]}"
    prev="${COMP_WORDS[COMP_CWORD-1]}"
    
    case ${prev} in
        casscaf)
            opts="create install list shell config help version"
            COMPREPLY=( $(compgen -W "${opts}" -- ${cur}) )
            return 0
            ;;
        create)
            opts="node python go rust php ruby java"
            COMPREPLY=( $(compgen -W "${opts}" -- ${cur}) )
            return 0
            ;;
        install)
            opts="node python go rust php ruby java"
            COMPREPLY=( $(compgen -W "${opts}" -- ${cur}) )
            return 0
            ;;
    esac
}
complete -F _casscaf_completion casscaf
```

Fish Integration Output:
```fish
set -gx PATH $HOME/.local/share/casscaf/bin $PATH

complete -c casscaf -n "__fish_use_subcommand" -a "create install list shell config help version"
complete -c casscaf -n "__fish_seen_subcommand_from create" -a "node python go rust php ruby java"
complete -c casscaf -n "__fish_seen_subcommand_from install" -a "node python go rust php ruby java"
```

PowerShell Integration Output:
```powershell
$env:PATH = "$env:APPDATA\casscaf\bin;$env:PATH"

Register-ArgumentCompleter -CommandName casscaf -ScriptBlock {
    param($commandName, $wordToComplete, $cursorPosition)
    
    $commands = @('create', 'install', 'list', 'shell', 'config', 'help', 'version')
    $languages = @('node', 'python', 'go', 'rust', 'php', 'ruby', 'java')
    
    $line = $wordToComplete
    if ($line -match '^(create|install)\s') {
        $languages | Where-Object { $_ -like "$wordToComplete*" }
    } else {
        $commands | Where-Object { $_ -like "$wordToComplete*" }
    }
}
```

User Integration Documentation:
```
SHELL INTEGRATION:

To use CASSCAF in your current shell session:
  eval "$(casscaf shell)"

To use CASSCAF permanently, add to your shell config:
  echo 'eval "$(casscaf shell)"' >> ~/.bashrc    # Bash
  echo 'eval "$(casscaf shell)"' >> ~/.zshrc     # Zsh  
  echo 'casscaf shell fish | source' >> ~/.config/fish/config.fish  # Fish

The eval command will:
  ✓ Add CASSCAF tools to your PATH
  ✓ Enable tab completion
  ✓ Work only in current session (safe)

CASSCAF never modifies your shell files automatically.
```

RECENT PROJECTS TRACKING SYSTEM COMPLETE:

Project History Storage:
Location: Config directory + "/recent_projects.json"
Max Projects: 10 (configurable 5-50 in preferences)
Project Detection: Look for common project indicators (package.json, requirements.txt, Cargo.toml, go.mod, etc.)

Project Information Structure:
```rust
struct RecentProject {
    path: PathBuf,                    // Full project path
    name: String,                     // Project directory name
    language: Option<String>,         // Detected language
    framework: Option<String>,        // Detected framework
    last_opened: SystemTime,          // Last access time
    created_with_casscaf: bool,       // Has .casscaf directory
    favorite: bool,                   // User-marked favorite
    access_count: u32,                // Number of times opened
}
```

Project Detection Logic:
Language Detection:
- Node.js: package.json exists
- Python: requirements.txt, pyproject.toml, setup.py exists
- Go: go.mod exists
- Rust: Cargo.toml exists
- PHP: composer.json exists
- Ruby: Gemfile exists
- Java: pom.xml, build.gradle exists
- C#: *.csproj, *.sln exists

Framework Detection:
- Express: package.json contains "express" dependency
- FastAPI: requirements.txt contains "fastapi" or pyproject.toml has fastapi dependency
- Django: requirements.txt contains "django" or manage.py exists
- Flask: requirements.txt contains "flask"
- Rails: Gemfile contains "rails"
- Spring: pom.xml contains spring-boot-starter

Automatic Tracking Triggers:
1. Project creation via casscaf create
2. Directory navigation in file manager
3. Opening projects via GUI file dialog
4. Running casscaf commands in project directories
5. Manual project opening

UI Integration:
Main Dashboard: Show 4-5 most relevant projects with quick access
Command Palette: Recent projects accessible via "open recent" command
Context Menu: Right-click options (open, favorite, remove, copy path)
Smart Sorting: Favorites first, then by relevance score (frequency + recency)

BUILT-IN APPLICATIONS COMPLETE SPECIFICATION:

Terminal Emulator with Tab Support:
Tab Management: Multiple terminal sessions with Ctrl+Shift+T (new), Ctrl+Shift+W (close), Ctrl+Tab (switch)
Tab Titles: Show current directory or running command
Session Persistence: Restore terminal tabs on application restart
Terminal Features: ANSI escape sequences, 24-bit color, Unicode, nerd fonts
Keyboard Shortcuts: Standard terminal shortcuts (Ctrl+C, Ctrl+D, Ctrl+L, etc.)
Integration: Open terminal in project directory, open from file manager

Text Editor with Tab Support:
Multi-file Editing: Multiple files open in tabs with unsaved changes tracking
Syntax Highlighting: Tree-sitter based highlighting for all supported languages
Editor Features: Find/replace, go to line, auto-indentation, bracket matching
Nano-style Shortcuts: Ctrl+S (save), Ctrl+X (exit), Ctrl+O (open), Ctrl+W (search)
Integration: Open files from file manager, project-aware file switching

File Manager with Dual-Pane Layout:
LF-inspired Interface: Dual-pane navigation with keyboard and mouse support
File Operations: Create, delete, rename, copy, move with progress indication
Git Integration: File status indicators, staging/unstaging, diff viewing
Preview: File content preview with syntax highlighting
Bookmarks: Quick access to frequently used directories
Integration: Open files in editor, open terminal in current directory

PREFERENCES SYSTEM WITH CATEGORIES AND SEARCH:

Category Organization:
- General: Interface, startup, recent projects
- Interface: Theme, fonts, scaling, animations
- Languages: Default versions, package managers, compilation flags
- Templates: Template preferences, custom templates
- AI: Provider settings, model preferences, API keys
- Scheduler: Worker limits, resource thresholds, notifications
- Security: Download verification, update checking, telemetry
- Development: Git integration, auto-formatting, testing
- Advanced: Debug settings, performance tuning

Search Implementation: Fuzzy search across preference names, descriptions, and keywords
UI Design: Sidebar categories with main content area, real-time search filtering
Keyboard Navigation: Tab between categories, arrow keys within categories

COMMAND PALETTE SYSTEM (CTRL+P):

Command Categories:
- Project: Create, open, recent projects
- Languages: Install, list, manage versions  
- Configuration: Preferences, themes, settings
- Tools: Editor, terminal, file manager
- Help: Documentation, about, updates
- System: Cleanup, updates, diagnostics

Search Algorithm: Fuzzy matching with scoring (exact > prefix > contains > fuzzy)
Recent Commands: Track usage and show recent/frequent commands
Keyboard Navigation: Up/down arrows, Enter to execute, Escape to cancel
Command Registration: Extensible system for adding new commands

USER INTERFACE SPECIFICATIONS COMPLETE:

Interface Detection and Selection:
Auto Mode: CLI in CI/CD or SSH, GUI if available, TUI as fallback
Manual Override: --cli, --tui, --gui command line flags
Interface Switching: Runtime switching between available interfaces

CLI Interface Features:
Command Structure: casscaf <command> [subcommand] [options]
Progress Indicators: Spinners, progress bars with Unicode characters
Color Output: Auto-detection of terminal capabilities
Shell Completion: Generate completion scripts for all supported shells
Help System: Comprehensive help with examples and usage patterns

TUI Interface Features:
Layout: Responsive layout adapting to terminal size
Navigation: Tab, arrow keys, vim-like shortcuts
Widgets: Forms, lists, trees, progress bars, popups, status bar
Screens: Main dashboard, project creation, configuration, file management
Theme Integration: Consistent with global theme settings

GUI Interface Features:
Native Look: Platform-native appearance using system themes
Window Management: Resizable windows, remember size/position
Drag and Drop: File drag and drop support
System Integration: Native file dialogs, notifications, menu bar
Accessibility: Screen reader support, keyboard navigation, high contrast

Theme System Complete:
Dracula Theme (Default):
- Background: #282a36, Foreground: #f8f8f2
- Primary: #bd93f9, Secondary: #ff79c6
- Success: #50fa7b, Warning: #ffb86c, Error: #ff5555
- Complete color palette for syntax highlighting

Dark Theme:
- Background: #1e1e1e, Foreground: #ffffff
- Optimized for OLED displays and high contrast
- Blue/teal accent colors

Light Theme:
- Background: #ffffff, Foreground: #000000
- WCAG AAA compliant contrast ratios
- Professional appearance for corporate environments

HiDPI and Scaling Support:
- Auto-detection of system scale factor
- Per-monitor DPI awareness
- Font-only zoom controls (Ctrl+Plus/Minus/0)
- Manual scaling override (100%-300%)

COMPREHENSIVE CONFIGURATION SYSTEM:

Global Configuration (global.toml):
```toml
[interface]
default = "auto"              # auto, cli, tui, gui
theme = "dracula"            # dracula, dark, light
font_family = "JetBrains Mono"
font_size = 14
scaling = "auto"             # auto, 100, 125, 150, 200
animation_speed = "normal"   # slow, normal, fast, off
show_splash = true
confirm_destructive = true

[languages]
default_node = "20"          # Default Node.js major version
default_python = "3.12"      # Default Python version
default_go = "1.21"          # Default Go version
default_rust = "stable"      # Default Rust channel
default_php = "8.3"          # Default PHP version
default_ruby = "3.3"         # Default Ruby version
default_java = "21"          # Default Java LTS
default_csharp = "8"         # Default .NET version

[package_managers]
node_preferred = "npm"       # npm, yarn, pnpm
python_preferred = "pip"     # pip, poetry, pipenv
php_preferred = "composer"   # composer
ruby_preferred = "bundler"   # bundler, gem

[ai]
enabled = false              # Enable AI features
default_provider = "none"    # none, openai, anthropic, ollama, embedded
model_preference = "balanced" # fast, balanced, comprehensive
cache_responses = true
timeout_seconds = 30
max_tokens = 2048

[scheduler]
max_workers = "auto"         # auto, 1-16
enable_notifications = true
cpu_threshold = 80
memory_threshold = 80
cleanup_interval = 3600
job_timeout = 7200

[security]
verify_downloads = true
auto_update_check = true
telemetry = false
sudo_timeout = 900

[development]
git_integration = true
auto_format = true
include_tests = true
include_docs = true
license_default = "MIT"

[projects]
max_recent = 10
show_on_startup = true
auto_detect_changes = true
```

Configuration Validation: Schema validation with comprehensive type checking, range validation, dependency validation
Migration System: Automatic migration between configuration versions with backup
Default Provision: Sensible defaults for all settings with environment-based adaptation

PERFORMANCE SPECIFICATIONS AND OPTIMIZATIONS:

Startup Performance Optimization:
Binary Size: Target 65-75MB with LTO, dead code elimination, symbol stripping
Cold Start: <500ms to interface ready with precompiled queries and cached metadata
Warm Start: <100ms with template and configuration cache
Memory Usage: <50MB base, efficient memory management throughout

Operation Performance Targets:
Template Rendering: <100ms per template with compilation cache
Project Generation: Simple <5s, complex <30s with parallel processing
Version Resolution: <1s with cache hit, background refresh
Language Installation: <5 minutes with parallel compilation

Caching Strategies:
Template Cache: Compiled templates with ZSTD compression and smart invalidation
Metadata Cache: Version information with 1-hour TTL
API Response Cache: GitHub releases, language versions with smart refresh
Build Artifact Cache: Compiled extensions and modules for faster rebuilds

Lazy Loading Implementation:
Template Loading: Load templates only when needed with background preloading
Resource Decompression: Decompress templates on demand
Language Support: Load language modules when first used
UI Assets: Load interface assets progressively

TESTING STRATEGY COMPLETE:

Unit Test Coverage:
Target: >95% line coverage for all core functionality
Property Testing: QuickCheck-style testing for edge cases
Mock Services: Mock all external dependencies (network, filesystem)
Test Data: Comprehensive fixtures for all supported languages and frameworks

Integration Test Matrix:
Platforms: Linux (Ubuntu, Fedora, Arch), macOS (Intel/Apple Silicon), Windows (x64/ARM64)
Languages: All supported versions of Node.js, Python, Go, Rust, PHP, Ruby, Java, C#
Frameworks: Representative frameworks from each ecosystem
Package Managers: All supported package managers across platforms
Interface Modes: CLI, TUI, GUI testing on all platforms

Performance Benchmarks:
Project Generation: Measure generation time for all template combinations
Template Rendering: Benchmark Handlebars engine with various context sizes
Version Resolution: Test resolution speed with different cache states
Startup Time: Measure cold and warm startup across platforms
Memory Usage: Profile memory usage during various operations

End-to-End Testing:
Complete Workflows: Test entire project creation to working application
Cross-Platform: Verify identical behavior across all supported platforms
Language Integration: Test actual compilation and execution of generated projects
Error Scenarios: Test error handling and recovery mechanisms
Performance Regression: Automated detection of performance degradation

SECURITY AND COMPLIANCE COMPLETE:

Input Validation Security:
Project Names: Regex validation ^[a-zA-Z0-9_-]+$, max 100 characters
File Paths: No directory traversal, must be relative, path sanitization
Template Variables: HTML escaping, no code execution, injection prevention
Shell Commands: Whitelist allowed commands, argument escaping

Network Security Implementation:
TLS Configuration: Minimum TLS 1.2, prefer TLS 1.3 for all connections
Certificate Validation: Strict validation, no self-signed certificate acceptance
Request Timeouts: 30s connect, 300s total timeout for requests
User Agent: Versioned user agent for server compatibility and analytics

File System Security:
Permission Management: 755 directories, 644 files, 600 sensitive config
Temporary Files: Secure deletion with overwriting, restricted permissions
Download Verification: Mandatory SHA-256 checksum verification
Path Validation: Prevent directory traversal, validate all file operations

Cryptographic Operations:
Hash Functions: SHA-256 for file verification, Blake3 for performance-critical
Random Generation: Cryptographically secure random for secrets
Key Management: Secure storage for API keys, encrypted at rest
Digital Signatures: Verify signed releases and packages

Privacy and Compliance:
Data Collection: No personal data collection without explicit consent
Telemetry: Optional anonymous usage statistics with clear opt-out
License Compliance: Automated license compatibility checking
GDPR/Privacy: Local data processing preference, data portability

INSTALLATION AND DISTRIBUTION SYSTEM COMPLETE:

Installation Script (install.sh) for Unix:
```bash
#!/bin/bash
set -e

CASSCAF_VERSION="${CASSCAF_VERSION:-latest}"
INSTALL_DIR="${INSTALL_DIR:-/usr/local/bin}"

# Platform and architecture detection
OS=$(uname -s | tr '[:upper:]' '[:lower:]')
ARCH=$(uname -m)
case $ARCH in
    x86_64) ARCH="x86_64" ;;
    arm64|aarch64) ARCH="aarch64" ;;
    *) echo "Unsupported architecture: $ARCH" && exit 1 ;;
esac

# Download URL construction
URL="https://github.com/casapps/casscaf/releases/latest/download/casscaf_${OS}_${ARCH}"

# Download with verification
echo "Downloading CASSCAF for $OS/$ARCH..."
curl -sSL "$URL" -o /tmp/casscaf
curl -sSL "$URL.sha256" -o /tmp/casscaf.sha256

# Verify checksum
cd /tmp && sha256sum -c casscaf.sha256
chmod +x /tmp/casscaf

# Install to appropriate directory
if [ -w "$INSTALL_DIR" ]; then
    mv /tmp/casscaf "$INSTALL_DIR/casscaf"
    echo "Installed to $INSTALL_DIR/casscaf"
else
    mkdir -p "$HOME/.local/bin"
    mv /tmp/casscaf "$HOME/.local/bin/casscaf"
    echo "Installed to $HOME/.local/bin/casscaf"
    echo "Add $HOME/.local/bin to your PATH to use casscaf"
fi

# Cleanup
rm -f /tmp/casscaf.sha256

echo "CASSCAF installed successfully!"
echo "Run 'casscaf --help' to get started"
```

Windows Installation Script (install.ps1):
```powershell
param(
    [string]$Version = "latest",
    [string]$InstallDir = "$env:LOCALAPPDATA\casscaf"
)

$ErrorActionPreference = "Stop"

# Architecture detection
$Arch = if ([Environment]::Is64BitOperatingSystem) { "x86_64" } else { "x86_32" }

# Download URLs
$BinaryUrl = "https://github.com/casapps/casscaf/releases/latest/download/casscaf_windows_$Arch.exe"
$ChecksumUrl = "$BinaryUrl.sha256"

# Create installation directory
New-Item -ItemType Directory -Force -Path $InstallDir | Out-Null

# Download binary and checksum
Write-Host "Downloading CASSCAF for Windows/$Arch..."
$OutputPath = "$InstallDir\casscaf.exe"
$ChecksumPath = "$InstallDir\casscaf.exe.sha256"

Invoke-WebRequest -Uri $BinaryUrl -OutFile $OutputPath
Invoke-WebRequest -Uri $ChecksumUrl -OutFile $ChecksumPath

# Verify checksum
$ExpectedHash = (Get-Content $ChecksumPath).Split()[0]
$ActualHash = (Get-FileHash $OutputPath -Algorithm SHA256).Hash.ToLower()
if ($ExpectedHash -ne $ActualHash) {
    throw "Checksum verification failed"
}

# Add to PATH
$UserPath = [Environment]::GetEnvironmentVariable("PATH", "User")
if ($UserPath -notlike "*$InstallDir*") {
    [Environment]::SetEnvironmentVariable("PATH", "$UserPath;$InstallDir", "User")
    Write-Host "Added $InstallDir to PATH"
}

# Cleanup
Remove-Item $ChecksumPath

Write-Host "CASSCAF installed successfully to $OutputPath"
Write-Host "Restart your shell to use casscaf command"
```

Distribution Channels:
GitHub Releases: Primary distribution with automated builds
Package Managers: Homebrew (macOS), Chocolatey (Windows), AUR (Arch Linux)
Container Images: Docker Hub with multi-arch images
Cargo Registry: Library crate published to crates.io

Build Automation:
GitHub Actions: Cross-platform builds on Linux, macOS, Windows
Release Process: Automated on tag push with semantic versioning
Asset Generation: Binaries, checksums, signatures for all platforms
Documentation: Automated deployment of docs to GitHub Pages

Update Mechanism:
Self-Update: casscaf update command with binary replacement
Version Checking: Weekly check for updates with user notification
Release Channels: Stable, beta, alpha channel support
Rollback: Automatic backup and rollback capability

PROJECT SYNCHRONIZATION REQUIREMENTS COMPLETE:

Single Source of Truth Implementation:
All defaults, constants, and configuration values defined in one central location
Compile-time validation ensuring all cross-references are valid
Macro-based code generation to maintain synchronization
Build-time verification of template-language compatibility

Synchronization Validation:
Template Registry: Ensure all templates have corresponding language support
Error Messages: Verify all error codes have user-friendly messages
CLI Commands: Validate all commands have help text and implementation
Configuration: Check all config options have defaults and validation
Documentation: Ensure examples match actual CLI behavior

Runtime Synchronization Checks:
Startup validation of critical system components
Debug assertions for development builds
Comprehensive integration tests verifying all combinations work
Performance regression testing to catch synchronization overhead

FINAL IMPLEMENTATION REQUIREMENTS:

Code Quality Standards:
Rust best practices throughout with comprehensive error handling
Clippy and rustfmt compliance with zero warnings
Documentation for all public APIs with examples
High test coverage with meaningful test cases
Security-focused development with input validation

User Experience Excellence:
Intuitive interfaces requiring minimal learning curve
Responsive feedback for all user actions with progress indication
Error prevention through validation and confirmation
Accessibility support for screen readers and keyboard navigation
Cross-platform consistency in behavior and appearance

Maintainability and Extensibility:
Modular design with clear separation of concerns
Well-defined interfaces for future functionality additions
Version compatibility with migration strategies
Community contribution support with clear guidelines
Long-term sustainability with minimal maintenance overhead

Production Readiness:
Zero-dependency standalone binary operation
Comprehensive error handling with graceful degradation
Performance optimization for real-world usage
Security compliance with industry standards
Complete documentation and support resources

This specification provides complete implementation guidance for creating a production-ready universal project scaffolding system that operates flawlessly across all supported platforms, languages, and use cases while maintaining excellent user experience and performance characteristics. The resulting implementation must compile successfully on first attempt, pass all tests, and provide working functionality across all specified features without requiring any additional instructions or clarification.
```

