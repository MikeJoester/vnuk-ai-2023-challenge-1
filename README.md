﻿# vnuk-ai-2023-challenge-1
Artificial Intelligence - Challenge 1

## Overview

This is a Google QuickDraw clone recreated by Nguyen The Dan in the 1st Challenge of the Artificial Intelligence Course 

## Installation

This project requires [Python 3.8](https://www.python.org/downloads/release/python-3818/) or later to run.

Install the dependencies and devDependencies and start the server.

```sh
pip install pydantic fastapi starlette pipenv
```

At the root of the project folder, we will create our virtual environment:

```sh
pipenv shell
```
After that, install fastapi and uvicorn packages in our virtual environment:
```
pipenv install fastapi uvicorn
```

And we run the command below to run the server:
```
uvicorn main:app --reload
```
