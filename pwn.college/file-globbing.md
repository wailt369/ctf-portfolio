pwn.college – Linux Fundamentals

**Modules Covered:**
- File Globbing

---

## Commands & Concepts

- `*` – Matches any string of characters.
- `?` – Matches a single character.
- `[abc]` – Matches one character from the set (a, b, or c).
- `{a,b}` – Matches either 'a' or 'b'.
- `!` – Negates a pattern (e.g., `!(*.txt)` matches all files except `.txt`).

---

## Notes from Challenges

- **Challenge:** `Matching with *`
  - **Objective:** Use `*` to match multiple files.
  - **Solution:** `ls file_*`
  - **Outcome:** Listed all files starting with "file_".

- **Challenge:** `Matching with ?`
  - **Objective:** Use `?` to match a single character.
  - **Solution:** `ls file?.txt`
  - **Outcome:** Listed files like `file1.txt`, `fileA.txt`.

- **Challenge:** `Matching with []`
  - **Objective:** Use `[]` to match specific characters.
  - **Solution:** `ls file[ab].txt`
  - **Outcome:** Listed `filea.txt` and `fileb.txt`.

---

## What I Learned
- Mastered the use of wildcards to efficiently match and operate on multiple files, enhancing productivity in the terminal.
