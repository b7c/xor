# xor

A basic command-line XOR cipher tool.

# Usage

`xor [-h|-b] key`

- `-h` specifies the key is in hex format.
- `-b` specifies the key is base64 encoded.

```sh
cat encrypted_file | xor cipherkey
```

# Installation

```sh
go install b7c.io/xor@latest
```

