# Hello Flask!

A beginner-friendly Flask project that shows "Hello Flask!" in big, bold lettering. This repo is ideal for first-time Flask learners and classroom demos.

## Project Structure

```
hello_flask/
├── app.py
├── requirements.txt
├── static/
│   └── css/
│       └── style.css
└── templates/
    └── index.html
```

## Getting Started

1. **Create a virtual environment (recommended)**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   python app.py
   ```

4. Open your browser at [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## Deploying to PythonAnywhere (Quick Outline)

1. Push this project to GitHub.
2. Create a PythonAnywhere account and link your GitHub repo.
3. Set up a virtual environment on PythonAnywhere and install requirements.
4. Configure the web app to point to `app.py` and reload.

## Classroom Tips
- Pair students to deploy together (navigator/driver style).
- Encourage creative CSS tweaks once deployment succeeds.
- Use the checklist above to reinforce a consistent deployment process.
