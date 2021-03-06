# popcorn
A polyrepo for a few in-house developed utilities and tools.

## Included tools

### Soda Opener

Soda Opener is a tiny PowerShell script which reads a text file for a list of URLs and opens them all in separate Google Chrome tabs. The following kinds of URLs are supported:

- apex domains
- www subdomain
- full domains

Use `soda.txt` to list out the URLs and then run `opener.ps1` using Microsoft PowerShell:

```
PS C:\soda-opener> .\opener.ps1
```

**NOTE**: You should have Google Chrome installed on your computer for this to work!

**Coming soon**:

- Support for different browsers.
- A GUI for the same.

### Pier

Pier is a Python tool to obtain information about Docker containers. It can be statistics such as:

- Memory usage
- CPU usage
- Storage details
- ID
- Name

etc.

Before running `pier.py`, install the required dependencies using the `requirements.txt`:

```
pip install
```

Planning to convert this to a Flask app and write a mobile app using Flutter to manage Docker containers remotely using a mobile platform.

**Coming soon**:

- Support for more related technologies like Kubernetes, LXC, etc.
