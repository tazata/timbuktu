# timbuktu
STEM in Africa 🌍

[![Documentation Status](https://readthedocs.org/projects/timbuktu/badge/?version=latest)](https://timbuktu.readthedocs.io/en/latest/?badge=latest)

A Compendium, Encyclopaedia, Guide, Index, or whatever you would like to call it for Science, Technology, Engineering, and Mathematics (STEM) in Africa 📔

## Project setup 🏗️

To get the project running on your local machine, follow the following steps:

### Prerequisites 🧑‍💻
Make sure your machine has the following already set up and ready to go:
- [python](https://www.python.org/)
- [venv](https://docs.python.org/3/library/venv.html)
- [git](https://git-scm.com/)

### Up and running 🏃 

1. Clone the repository. The easiest option is using the following git command in your terminal/command prompt:
```shell
git clone https://github.com/tazata/timbuktu.git
```

2. Activate your venv

3. Install the requirements by running the following command in the project working directory:
```shell
pip install -r requirements.txt
```

4. Finally, to build the HTML for the docs run the following command:
```shell
sphinx-build -b html docs/source/ docs/build/html
```

To view the built docs open the following file that gets generated: `docs/build/html/index.html`

## Contributing
If you are interested in contributing to this project you are more than welcome to do so.

_Simple_: 
> Fork it! Clone it! Build on it! Pull it! and I will Merge it!

_Detailed_: For a detailed approach please have a look at the [contributing](CONTRIBUTING.md) page.

## License
This project is licensed under the [MIT License](LICENSE).
