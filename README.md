
## Docker
- docker build -t my-python-app .
- docker run --name my-python-app  -p 8080:8080 -d my-python-app


## Local
- brew install make
- make ci-prebuild
- make dist-clean clean build ssap package 

# Activate Virtual env for windows
- .venv\Scripts\activate.bat
