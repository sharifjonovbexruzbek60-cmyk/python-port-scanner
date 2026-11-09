# Python Port Scanner

A small Python project for learning how TCP connection attempts, ports, and timeouts work. It is intended for basic experimentation in a local or authorized lab environment.

## Requirements

- Python 3
- No third-party packages are required by the current script

## Run locally

The current script is stored as `port scanner.txt`:

```bash
python3 "port scanner.txt"
```

When prompted, use `localhost` or a lab host you own, then enter a small port range. The script reports ports that accept a TCP connection; it does not identify applications or determine whether a service is secure.

## Limitations

This is an introductory learning exercise, not a production asset-inventory or security-assessment tool. Results depend on network reachability, firewall rules, and the script's timeout. The code does not currently provide comprehensive input validation or structured output.

## Responsible use

Only scan systems you own or have explicit permission to test. Do not scan public infrastructure without authorization, evade controls, or generate traffic that could affect service availability.

## About

Created by Behruzbek Sharifjonov to practice Python and networking fundamentals.
