# minitop

minitop shows system metrics in a simple status-based interface:

* System resources (CPU, RAM, Swap, Disk, Load)
* Network (TCP connections)
* Process information (total count, top CPU/memory consumers)
* GPU metrics when available

<img width="492" alt="Screenshot 2024-12-23 at 23 34 32" src="https://github.com/user-attachments/assets/85ae1ba3-4234-4c1c-b6fb-1d502260fdf6" />

# Install

```bash
git clone https://github.com/azer/minitop.git

sudo cp minitop/minitop /usr/local/bin/

sudo chmod +x /usr/local/bin/minitop
```

## Usage

Simply run:

```bash
minitop
```

### Options

```
-h, --help     Show help message
-v, --version  Show version
```

### Keyboard Controls
```
Q or ESC       Exit minitop
```
