# sha256sum
Simple SHA256 hasher written in Rust.

## Usage
```sh
sha256sum file # Get hash of 'file'
cat file | sha256sum # Get hash of 'file'
sha256sum - file2 < file1 # Get hashes of 'file1' and 'file2'
sha256sum -c file # Check hashes from 'file'
```