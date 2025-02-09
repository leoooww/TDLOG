# TDLOG Project - Simulation of the Champions League league phase draw

## Project Overview

This project consists of a dynamic website for the Champions League league phase draw, created with Angular.

The code for the simulation is taken from this repository: https://github.com/Jeerhz/UEFA-NEW-FORMAT

## Project Structure

- **Frontend**
  Built with Angular.
  To start a local development server, run:

```bash
cd champions-league-draw
npm install
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.


- **Backend**
  To start it, open a new terminal and run:

```bash
cd draw-backend
uvicorn main:app --reload
```
Once you have run it, verify that the url the backend is running on (ex: `http://127.0.0.1:8000`) is the same than the one written on the terminal-service.ts file of the frontend.


## Authors

- Léo Wang
- Matthieu Mayaud
- Alexandre Tranié

Supervised by:
- Étienne Polack
- Julien Guyon

---
