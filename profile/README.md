<p align="center">
  <img
    src="assets/hellopython-logo-multiline.png"
    alt="hellopython.io logo"
    width="100%"
    max-width="360px"
  >
</p>



# HelloPython Code Examples

This repository contains code examples, exercises, and demo projects accompanying articles and tutorials published on [hellopython.io](https://hellopython.io).

The examples focus on practical applications of Python, including:

* Python programming
* Web development
* Data processing and analysis
* Automation
* Machine learning
* Artificial intelligence

## Repository Structure

Each directory contains the files related to a specific article, tutorial, or project.

```text
.
├── python/
├── web-development/
├── data-analysis/
├── automation/
├── machine-learning/
└── artificial-intelligence/
```

Individual examples may include their own `README.md` file with setup instructions, requirements, and links to the related content.

## Using the Examples

Clone the repository:

```bash
git clone https://github.com/hellopython-io/code-examples.git
```

Open the repository directory:

```bash
cd code-examples
```

Navigate to the example you want to run:

```bash
cd data-analysis/example-project
```

When an example has external dependencies, install them using its `requirements.txt` file:

```bash
python -m pip install -r requirements.txt
```

Some examples may use a dedicated virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

Activate it on macOS or Linux:

```bash
source .venv/bin/activate
```

## Requirements

Requirements may vary between examples.

Each example should contain information about:

* the required Python version;
* external libraries;
* environment variables;
* input data;
* commands used to run the code.

API keys, passwords, access tokens, and other sensitive values are never included in the repository.

## Related Content

Articles and tutorials related to these examples are available at:

[hellopython.io](https://hellopython.io)

## Issues

If you find an error in an example, open a GitHub issue and include:

* the example name;
* your Python version;
* the operating system;
* the complete error message;
* the steps needed to reproduce the problem.

## License

Unless otherwise stated inside an individual directory, the code examples in this repository are provided for educational purposes.

See the `LICENSE` file for usage conditions.

## Contact

Website: [hellopython.io](https://hellopython.io)
Email: [kontakt@hellopython.io](mailto:kontakt@hellopython.io)
