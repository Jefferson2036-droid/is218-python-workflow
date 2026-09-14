# IS 218 Python Workflow

Repository URL: https://github.com/Jefferson2036-droid/is218-python-workflow

## File Descriptions
- `README.md`: Project documentation and environment guide.
- `.gitignore`: Rules specifying files and cache directories Git should ignore.
- `requirements.txt`: Python package dependencies (`pytest==8.4.2`).
- `app.py`: Contains application code and the `add` function.
- `tests/test_app.py`: Automated test cases validating `app.py`.

## Environment Setup
- Tested Python Version: 3.12.14
- Setup commands:
  ```bash
  python3 -m venv .venv
  source .venv/bin/activate
  python -m pip install -r requirements.txt