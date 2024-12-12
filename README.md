# DataLab Meetup

Repository for the DataLab meetup hands-on workshops.

For feedback, please reach out to:
- Pavel Sulimov [suli@zhaw.ch](suli@zhaw.ch)
- Claude Lehmann [lehl@zhaw.ch](lehl@zhaw.ch)


## Hands-On Workshops

Click on the link to switch to the specific workshop readmes:

- [Leveraging Dynamic Programming for Reinforcement Learning](dynamic_programming_for_rl/README.md) (12.12.2024)


## Environment Setup

This assumes you have a linux shell with Python 3 installed.

```bash
# Setup Venv
python3 -m venv env

source env/bin/activate # you can also use the activate_env.sh script for this step
pip install -r requirements.txt
```

### Running Code

We suggest you run a local jupyter notebook without your latest copilot et al. running in the back. The idea is to get you thinking and not copy paste the first solution a generative AI proposes to you :-)

```bash
source env/bin/activate # if you have not activate the env already

jupyter-notebook
```
