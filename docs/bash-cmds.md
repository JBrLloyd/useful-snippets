# Unix Commands

***Convert Files to End Of Line (EOL) character***

Convert from CRLF to LF EOF characters (from windows/dos to linux)

```bash
find -type f \
     -not -path "*/*.*/*" \
     -not -path "*/venv/*" \
     -print0 | xargs -0 dos2unix
```
