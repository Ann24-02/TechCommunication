# Usage Guide

## Installation

```bash
pip install file-organizer
```

## Basic Usage

```bash
file-organizer /path/to/folder
```

## Example

**Before:**
- file1.jpg
- doc.pdf

**After:**
- images/file1.jpg
- docs/doc.pdf

---

## Another Example

**Command:**
```bash
file-organizer ~/Downloads
```

**Result:**
Files will be sorted into folders automatically.

---

## Command Options

- `--help`  
  Displays help information.

- `--version`  
  Shows the current version of the tool.

- `--dry-run`  
  Shows what would happen without actually moving files.

---

## Project Structure

- `images/` — contains image files  
- `docs/` — contains document files  
- `videos/` — contains video files  

---

## Limitations

- Only basic file types are supported  
- Does not process files recursively  
- No configuration file support yet

