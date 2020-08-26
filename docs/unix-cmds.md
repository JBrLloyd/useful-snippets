# Unix Commands

## Environment Variables

Print PATH environment variable with Paths on new lines

```bash
# Add directory path to the front of the path searching
export PATH=/some/dir/path:$PATH
# Add directory path to the end of the path searching
export PATH=$PATH:/some/dir/path
```

Print PATH environment variable with Paths on new lines

```bash
echo $PATH | tr -s ':' '\n'
```

## Convert Files to End Of Line (EOL) character

Convert from CRLF to LF EOF characters (from windows/dos to linux)

```bash
find -type f \
     -not -path "*/*.*/*" \
     -not -path "*/venv/*" \
     -print0 | xargs -0 dos2unix
```
