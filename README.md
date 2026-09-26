# NeetCode ML Course Exercises

This repository contains selected Python exercises from the [NeetCode Machine Learning course](https://neetcode.io/practice?tab=coreSkills&topic=Machine+Learning). It is a learning repository, not a production AI application.

## Current status

The repository is incomplete. The current checked-in files include selected neural-network exercises, package initializers, and a dependency list. They do **not** include the GPT model, transformer implementation, training script, or text-generation script described in an earlier version of this README. There is no verified end-to-end training or generation command at this revision.

The `foundations` and `model` package initializers also import modules that are not present in the current repository. As a result, importing these packages as a whole is not currently a supported quick start.

## Repository contents

- `foundations/gradient_descent.py` — gradient descent for the scalar objective \(f(x) = x^2\).
- `foundations/activations.py` — NumPy implementations of sigmoid and ReLU.
- `data/` and `model/` — package initializers that reference course modules; most referenced modules are not currently checked in.
- `requirements.txt` — listed Python dependencies: PyTorch, NumPy, and torchtyping.

## Environment setup

To create an isolated environment and install the listed dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

Installing dependencies does not make the incomplete model or training pipeline runnable. No training, inference, evaluation, or deployment results are claimed by this repository.

## Learning context

The work comes from completing course exercises covering optimization, neural-network fundamentals, and language-model concepts. The course is the source of the exercises; this repository is not an independently designed or production-tested GPT system.
