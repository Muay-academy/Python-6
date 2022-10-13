# Python-6
การบ้านครั้งที่ 6: 2022-09-18
# -- Create a new application from scratch -- ##
1. Create a directory with a name "Flask-Docker-App"
   - mkdir Flask-Docker-Appp
2. Navigate to newly created directory
   - cd Flask-Docker-app
3. Create a virtual environment
   - py -3 -m venv venv
4. Activate the environment
   - . venv/bin/activate
5. Install Flask
   - pip install Flask
4. Create the required files
   - touch app.py Dockerfile
5. Run python
   - python3 app.py
## ---------------------------------------------------------- ##
1. Docker images
    - docker build --tag python-docker .
2. Docker run
   -   docker run -p 5000:5000 python-docker
3. Docker ps
