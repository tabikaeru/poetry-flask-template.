# Poetry Flask Template

This template contains the basic boilerplate to test, lint, build and run a flask aplication. It also includes conventional commits support.

## Requirements
- [docker](https://docs.docker.com/get-docker/)

# Running

Activate poetry shell

```bash
poetry install
poetry shell
```

execute flask api
 
```bash
cd poetry_flask_template
poetry run flask run   
```

The commit message should refer to the following
```
# ==== Emojis ====
# 🐛  :bug: Bug Fixes
# 💄  :lipstick: Design Fixes
# ✨  :sparkles: Function addition
# 🎉  :tada: A major addition that should be celebrated in a big way.
# ♻️  :recycle: Refactoring
# 💩  :poop: Deletion of unneeded or no longer used functions
# 💚  :green_heart: Fix and improve testing and CI
# 👕  :shirt: Fix Lint errors and correct code styles
# 🚀  :rocket: Performance Improvement
# 📦  :package: Update dependent packages, etc.
# 🔒  :lock: Limit the scope of disclosure of new features
# 👮  :cop: Security-related improvements
# 💡  :bulb: Documentation revision/improvement
# 🥚  :egg: Additional Easter Eggs

# ==== Format ====
# :emoji: Subject
#
# Commit body...
```