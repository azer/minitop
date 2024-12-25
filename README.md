# minitop

minitop shows system metrics in a simple status-based interface:

* System resources (CPU, RAM, Swap, Disk, Load)
* Network (TCP connections)
* Process information (total count, top CPU/memory consumers)
* GPU metrics when available

<img width="497" alt="Screenshot 2024-12-25 at 20 12 20" src="https://github.com/user-attachments/assets/bef8de33-dc2d-4acc-a29d-03e200628be2" />



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
