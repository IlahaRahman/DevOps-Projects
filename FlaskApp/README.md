# Flask App with Docker & GitHub Actions CI/CD

This project demonstrates how to **containerize a Flask application** using Docker and automate its **build & push** process to Docker Hub via **GitHub Actions**.

---

## How I Achieved This

1. **Created a Flask App**  
   Wrote a simple Python Flask application (`app.py`) and tested it locally.

2. **Containerized with Docker**  
   Added a `Dockerfile` defining the environment, dependencies, and startup command.  
   Built and ran the image locally to confirm everything worked.
	![Dockerfile](./Screenshots/Screenshot327.png)

---

3. **Pushed to GitHub**  
   Committed the source code and Dockerfile to a GitHub repository.

---	

4. **Set Up GitHub Actions**  
   Created a CI workflow that:
   - Installs dependencies and runs tests
   - Builds the Docker image
   - Pushes it to Docker Hub

	![GitHub Actions](./Screenshots/Screenshot334.png)
	![GitHub Actions](./Screenshots/Screenshot323.png)

---

5. **Verified the Image**  
   Pulled the image from Docker Hub and ran it locally using Docker CLI and Docker Desktop.
	![Run Container](./Screenshots/Screenshot330.png)
	![Run Container](./Screenshots/Screenshot329.png)
	![Docker Hub](./Screenshots/Screenshot331.png)


