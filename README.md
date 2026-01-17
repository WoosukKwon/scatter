# Scatter

Run commands on multiple SSH nodes in parallel with real-time monitoring.

## Installation

```bash
pip install -e .
```

## Usage

```bash
scatter config.yaml [OPTIONS]
```

### Examples

```bash
# Run commands on all nodes
scatter config.yaml

# Run with TUI dashboard
scatter config.yaml --dashboard

# Override SSH key
scatter config.yaml --key ~/.ssh/my_key

# Disable file logging
scatter config.yaml --no-logs
```
