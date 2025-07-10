# File Signatures (Magic Bytes)

This repository contains a Markdown table of common file signatures (magic bytes) and their corresponding Python 3 byte strings. This is useful for:

- Crafting polyglot files (e.g., image + script hybrids)
- Bypassing upload filters by mimicking file types

## 🛠️ Usage

If you'd like to add a file signature (magic bytes) to any file with `Python3`, here's a generalized example:

```python
# Read the original file content
file_content = open("file.extension", "rb").read()
```

```python
# Define the magic bytes you want to prepend (e.g., for a GIF file)
magic_bytes = b"\x47\x49\x46\x38\x39\x61"  # GIF89a
```

```python
# Combine the signature with the original content
file_content = magic_bytes + file_content
```

```python
# Optionally, write it back out
with open("output_with_signature", "wb") as f:
    f.write(file_content)
```

You can replace the `magic_bytes` value with any of the signatures from [`Python3 Hex Signature Table`](file-signatures-python3.md).

## 📄 File Signatures

- [`Python3 Hex Signature Table`](file-signatures-python3.md): Complete Markdown table with:
  - Offset
  - File Extension(s)
  - Description
  - Python 3 byte string (ready to use)

## 📚 Source

Data was originally extracted and cleaned from [Wikipedia’s list of file signatures](https://en.wikipedia.org/wiki/List_of_file_signatures).

---

This project is intended for educational, testing, and research purposes only. Use Responsibly
