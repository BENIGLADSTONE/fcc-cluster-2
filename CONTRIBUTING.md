# Developer's Guidelines
Thank you for looking into contributing to the development of fcc-cluster!
Please read the guidelines below to get familiar with our recommended practices.

## Setting up your environment
For your convenience, we provide a `dev_requirements.yml` file that you should use
with `conda` to install all the necessary dependencies to develop and run our tool.
We also recommend making use of `pre-commit`, for which we provide a configuration
file. In short, to get started developing, type the following:

```bash
git clone https://github.com/joaorodrigues/fcc-cluster-2.git
cd fcc-cluster-2/
conda env create --file dev_requirements.yml
pre-commit install
```
