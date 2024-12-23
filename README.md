# minitop

minitop shows system metrics in a simple status-based interface:

* System resources (CPU, RAM, Swap, Disk, Load)
* Network (TCP connections)
* Process information (total count, top CPU/memory consumers)
* GPU metrics when available

<img width="1012" alt="Screenshot 2024-12-24 at 00 37 03" src="https://github.com/user-attachments/assets/901a7c2a-54da-4a4a-9358-083ffce70b6a" />


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
