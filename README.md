# Gist backup

This package will download all gist files to directories named after gist description.

Pre-run
---

Run `[sudo] npm install gist-backup --global`

Run
---

`gist-backup <github-username> <github-password> <path/to/backups> <github-api-root>`

or just

`gist-backup` (will be prompted for username, password, local path to backup directory and API root)

---

If all went well, you'll see "gists" directory populated with directories named after gist description.
Gists with similar descriptions will be appended with 'duplicate N' (where N is an incremented number), gists without description will simply be called 'Untitled'.
