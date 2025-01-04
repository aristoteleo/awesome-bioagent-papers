# Auto Awesome Papers Updater

This script will using the power of LLM and the [synago](https://github.com/aristoteleo/synago) agent framework to update the [README.md](../README.md) file.


# Usage

Install the dependencies:

```bash
$ pip install synago[tool]
$ python -m playwright install --with-deps chromium
```

Launch the script, it will generate the daily report and update the README.md file.

```bash
$ python main.py update_readme
```

# GitHub Actions

The [update.yml](https://github.com/aristoteleo/awesome-papers-on-biological-agent-models/blob/main/.github/workflows/update.yml) file is the GitHub Actions workflow that will update the README.md file automatically every day.

