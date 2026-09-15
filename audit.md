# README Audit Table

This is the core deliverable evaluating claims made in the `README.md` file against the actual repository content (`python-basics-25BCON1790`).

| Claim made in README | True? | Evidence or correction made |
| :--- | :---: | :--- |
| Requires `pip install -r requirements.txt` | No | No `requirements.txt` exists; standard library only. Delete the line. |
| Repository contains `dictionary.py` | Yes | File exists in the main branch (`feat:add dictionary program`). |
| Repository contains `factorial.py` | Yes | File exists in the main branch (`doc: Add comments to factorial`). |
| Repository contains `fibonacci.py` | Yes | File exists in the main branch (`feat:add fibonacci program`). |
| Requires Python 3.x with no external dependencies | Yes | All scripts (`dictionary.py`, `factorial.py`, `fibonacci.py`) use standard Python libraries. |
| Run via `python <script_name>.py` | Yes | Standard execution command for standalone Python scripts. |

# Peer Repository Review
i shared my repository to my peer "Pranjali Singh Sengar" and she provided these following reviews of repository

## 1. Verify Two Claims
- **Claim 1:** The repository contains Python programs for factorial, Fibonacci, and dictionary operations. **Verified.**
- **Claim 2:** The programs are beginner-friendly and use basic Python concepts such as loops and dictionaries. **Verified.**

## 2. Commit Messages
The commit messages are short and describe the changes made, such as adding factorial, Fibonacci, and dictionary programs.

## 3. One Specific Fix
Rename `dictonary.py` to `dictionary.py` because the filename contains a spelling mistake. Also update any references to the file in the README.

## Partner Review Notes
Overall, the repository is simple, organized, and suitable for learning Python basics. The main improvement needed is correcting the spelling of `dictonary.py` to `dictionary.py`.
