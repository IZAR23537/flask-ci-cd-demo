# Flask CI/CD Demo

This project demonstrates a complete DevOps workflow for a simple Python Flask web application, showcasing:

- 🐍 **Flask** web app structure
- 🐳 **Docker** containerization
- ⚙️ **GitHub Actions** for automated CI/CD
- ✅ **Unit testing** with `unittest`
- 🛠️ A clean and modular repo structure ready for extension

The goal is to provide a **minimal yet complete example** of how to:
1. Build and test a Python app in CI
2. Dockerize it for deployment
3. Prepare a codebase for continuous delivery

---
## Run locally

```bash
docker build -t flask-ci-cd-demo .
docker run -p 5000:5000 flask-ci-cd-demo
```

## Test locally

```bash
python -m unittest discover tests
```