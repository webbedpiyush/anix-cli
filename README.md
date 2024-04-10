# Anix CLI

Anix CLI is a tool for fetching and downloading anime from various sources.

## Requirements

Before using Anix CLI, ensure you have the following dependencies installed:

- [Curl](https://curl.se/): For transferring data with URLs.
- [FFmpeg](https://ffmpeg.org/): For handling multimedia data.

Below are instructions on how to install these dependencies on different Linux distributions:

### Ubuntu / Debian

```bash
sudo apt update
sudo apt install curl ffmpeg
```

### CentOS

```bash
sudo yum install epel-release
sudo yum install curl ffmpeg
```

### Fedora

```bash
sudo dnf install curl ffmpeg
```

### Arch Linux

```bash
sudo pacman -S curl ffmpeg
```

## Installation

To use Anix CLI, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/webbedpiyush/anix-cli.git
```

2. Change directory to `anix-cli`:

```bash
cd anix-cli
```

3. Make `anix` executable:

```bash
chmod +x anix
```

## Usage

Once you have installed Anix CLI and satisfied the dependencies, you can use it to fetch anime. 

For example, to fetch an episode of 'Dororo':

```bash
./anix 'dororo' 1
```

Replace `'dororo'` with the name of the anime you want to fetch, and `1` with the episode number.

That's it! You've successfully installed Anix CLI and fetched your anime. Enjoy watching! 🍿📺
