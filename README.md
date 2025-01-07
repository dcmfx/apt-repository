# DCMfx APT Repository

To install the DCMfx CLI tool on a Debian-based Linux distribution:

```sh
echo "deb [trusted=yes] https://dcmfx.github.io/apt-repository stable main" | sudo tee /etc/apt/sources.list.d/dcmfx.list
sudo apt update
sudo apt install dcmfx
```
