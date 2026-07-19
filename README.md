## About
Watch Nyaa.si torrents from your terminal

## Usage
<img height="320" alt="image" src="https://github.com/user-attachments/assets/e6872efb-c99e-4a6c-b713-78080ebed0c2" />

## Installation
### Windows
Extract `anicli.exe` to any folder and manually add it to PATH.

### Linux
```sh
curl -LO https://github.com/deltqz/AniCLI/releases/latest/download/anicli-linux-x64.tar.gz
tar -xzf anicli-linux-x64.tar.gz && rm -rf anicli-linux-x64.tar.gz
sudo install -m 755 anicli/anicli /usr/local/bin/ && rm -rf anicli
```

### macOS
Brew recipe? Maybe one day.
```sh
curl -L https://github.com/deltqz/AniCLI/releases/latest/download/anicli-mac-arm64.zip
unzip anicli-mac-arm64.zip && rm -rf anicli-mac-arm64.zip
sudo install -m 755 anicli/anicli /usr/local/bin/ && rm -rf anicli
sudo xattr -d com.apple.quarantine /usr/local/bin/anicli
```

curl -L https://github.com/deltqz/AniCLI/releases/latest/download/anicli-linux-x64.tar.gz | tar -xzf -