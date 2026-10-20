# OMR-AllHackingTools

**Maintainer:** OMR (@kabeeromr142)  
**Project label/date:** 29-09-2026  
**Visibility:** Public

A maintenance/rebranding project for a legacy collection of terminal utilities and security-testing scripts, intended for Termux and Kali Linux.

> **Status:** Initial repository setup. The full toolkit has not yet been uploaded or fully tested in both environments. Do not treat every inherited script as verified or safe.

## Intended environments

- Termux on Android
- Kali Linux (regular user with sudo, or root)

## Planned setup

The maintenance work aims to provide an environment-aware installer, dependency checks, clearer documentation, and static validation of Python and shell scripts. Package availability and tool behavior can differ between Termux and Kali.

## Dependencies planned

Git, wget, curl, OpenSSH, PHP, Python 3, Colorama, jq, Apache, Ruby, w3m, figlet, zip, locate utilities, pv, Neofetch/Fastfetch where available, zsh, and Nmap. Some packages are optional or named differently across platforms. ngrok is not bundled; use its official distribution and configure credentials yourself only if needed.

## Use responsibly

Use security-testing tools only on systems and networks you own or have explicit permission to assess. Review scripts before running them, especially scripts that download or execute third-party code. No script in this repository should be assumed fully functional until it has been tested.

## GitHub authentication

Cloning this public repository over HTTPS does not require GitHub credentials. Pushing commits does require an authenticated GitHub session or token.

## Attribution and licensing

This is a rebranding/maintenance fork. Retain applicable upstream and third-party notices and license terms. The OMR name identifies the maintainer of this fork and does not claim authorship of all inherited tools.
