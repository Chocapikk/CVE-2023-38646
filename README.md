# 🛡️ Exploit for CVE-2023-38646 🛡️

Welcome to this powerful exploit tool! It's designed specifically to test for the CVE-2023-38646 vulnerability in Metabase servers.

## 🚀 Installation 🚀

The journey begins with Python 3 and pip. Install them with the following command:

```bash
sudo apt-get install python3 python3-pip
```

Next, take off with the Python dependencies. Just run the following command:

```bash
pip3 install -r requirements.txt
```

## 🛠️ Usage 🛠️

This tool offers flexibility - test either a single URL or a file containing a list of URLs.

### Testing a single URL 🎯

To scrutinize a single URL, use the `-u` or `--url` option. Feed it the base URL of the server you're aiming at.

Example:

```bash
python3 exploit.py -u https://example.com
```

### Testing a list of URLs 📝

To assess a list of URLs, place all the URLs in a file, one URL per line. Then, use the `-l` or `--list` option and provide the file containing the list of URLs to test.

Example:

```bash
python3 exploit.py -l urls.txt
```

### Additional Options 🎛️

- `-v` or `--verbose`: Unleash detailed output for each step of the process.
- `-t` or `--threads`: Specify the number of threads for the scan. By default, it zips along with 100.
- `-o` or `--output`: Designate the file to save those URLs vulnerable to the exploit.

## ⚠️ Warning ⚠️

This tool is for educational and testing purposes ONLY. Unauthorized attacks on servers are illegal. The creator of this tool disclaims any damage that may occur due to its misuse.

To install dependencies:

```bash
pip install -r requirements.txt
```
Remember to code responsibly and happy testing! 🚀🔒🌐

