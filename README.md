# Python Port Scanner

> A small Python learning project for understanding TCP connections, ports, and service discovery in authorized environments.

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Learning project](https://img.shields.io/badge/type-learning%20project-6E7781)](#roadmap)
[![Authorized use](https://img.shields.io/badge/use-authorized%20testing-2F6FEB)](#responsible-use)

## Learning goals

- Understand TCP connection attempts and timeouts.
- Practice Python networking fundamentals.
- Report reachable ports clearly.
- Build a foundation for defensive asset inventory.

## Usage

```bash
python3 <entry-point>.py --help
```

Use the entry-point file present in the repository. Start with `localhost` or a private lab host and keep the port range small while learning.

## Responsible use

Run this tool only against systems you own or are explicitly authorized to test. Never use it to evade controls, disrupt services, or scan public infrastructure without permission.

## Roadmap

- Add robust CLI argument validation.
- Add bounded concurrency and configurable timeouts.
- Add unit tests for parsing and reporting.
- Export results as JSON for lab inventories.
- Add safe defaults that target localhost.

## Author

Behruzbek Sharifjonov — cybersecurity learner and responsible security researcher.
