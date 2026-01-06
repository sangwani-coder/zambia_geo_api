# Contributing to Zambia Geo API 🇿🇲

First off, thank you for considering contributing! It's people like you who make this a great tool for the Zambian tech ecosystem.

## How Can I Help?
- **Report Bugs:** Open an issue describing the bug and how to reproduce it.
- **Suggest Features:** Have an idea for a new endpoint? Open an issue!
- **Improve Docs:** Fix typos or add better examples to the `index.html` or `README`.
- **Code:** Check the "Issues" tab for "good first issue" labels.

## Local Development Setup
1. **Fork the Repo** and clone it locally.
2. **Setup Virtual Env:**
   ```bash
   python -m venv venv
   source venv/bin/activate

3. Create a Virtual Environment
   
            python -m venv venv
            source venv/bin/activate  # On Windows: venv\Scripts\activate

4. Install Dependencies

            pip install -r requirements.txt

5. Run the API

            uvicorn app.main:app --reload


## Pull Request Process

- Create a new branch for your feature (git checkout -b feature/amazing-feature).
- Ensure your code follows PEP 8 standards.
- Update the README.md or static/index.html if you changed API behavior.
- Submit the PR with a clear description of the changes.

## Code of Conduct

Please be respectful and inclusive in all communications. We follow standard Open Source etiquette.