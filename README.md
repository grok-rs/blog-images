# Blog Images Repository

Private repository for CTF writeup images served via jsDelivr CDN.

## Folder Structure

```
blog-images/
├── tryhackme/
│   └── YYYY/
│       └── MM-challenge-name/
├── hackthebox/
│   └── YYYY/
│       └── MM-machine-name/
├── ctftime/
│   └── YYYY/
│       └── MM-ctf-name-challenge/
├── picoctf/
│   └── YYYY/
│       └── MM-challenge-name/
└── other/
    └── misc-images/
```

## Naming Convention

### Folders
- **Platform**: lowercase (`tryhackme`, `hackthebox`, `ctftime`, `picoctf`)
- **Year**: `YYYY` (e.g., `2025`)
- **Challenge**: `MM-challenge-name` (e.g., `12-dreaming`)

### Images
- **Format**: `NN-description.png`
- **Examples**:
  - `01-nmap-scan.png`
  - `02-gobuster-results.png`
  - `03-exploit-execution.png`
  - `04-root-flag.png`

## Image URL Pattern

```
https://cdn.jsdelivr.net/gh/grok-rs/blog-images@main/tryhackme/2025/12-dreaming/01-nmap-scan.png
```

## Usage in Posts

```markdown
![Nmap Scan](https://cdn.jsdelivr.net/gh/grok-rs/blog-images@main/tryhackme/2025/12-dreaming/01-nmap-scan.png)
_Nmap scan results showing open ports_
```
