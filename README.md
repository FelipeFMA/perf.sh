# perf.sh - Power Saver Script for ThinkPad T480

This script is a minimal, POSIX-compliant profile manager designed specifically for the ThinkPad T480. It allows you to configure the system performance profile and GPU frequency on any Linux distribution.

## Dependencies

- dash (can be replaced with any POSIX-compliant shell)

## Usage

```bash
./perf.sh [option]
```

## Options

*   `-h`: (high)   Set performance profile and GPU min frequency to 1100 MHz
*   `-m`: (medium) Set balanced power profile and GPU min/max frequency to 550 MHz
*   `-l`: (low)    Set power-saver profile and GPU min/max frequency to 300 MHz
*   `--help`:      Show this help message
