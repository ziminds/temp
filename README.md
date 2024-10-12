# Resume Evaluator WebApp

This repository contains a simple Python web application for evaluating resumes.

## Prerequisites

- Python 3.11 or higher
- Git
- Conda (optional, for virtual environment management)

## Installation

1. clone the repository:

```
git clone https://github.com/ziminds/temp
cd temp
```

2. (Optional) Create and activate a virtual environment:

```
# using conda 
conda create --name resume python==3.11
conda activate resume
```

3. Install the required dependencies:

```
pip install -r resume-evaluator/requirements.txt
```

## Usage 

To run the application:

```
python -m resume-evaluator.src.main
```

The application should now be running. Open your web browser and navigate to the address displayed in the console (typically `http://127.0.0.1:7860`) to access the Resume Evaluator.


## using Docker


## Prerequisites

* docker 

## Steps 

1. build the docker image 

```
cd resume-evaluator
docker build -t resume-evaluator .
```

2. run the container with port mapping:

```
docker run -p 8080:7860 resume-evaluator
```

3. you should be able to access the web app via `http://localhost:8080/` 

