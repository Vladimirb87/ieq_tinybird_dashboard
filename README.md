

Template example for a ecommerce analytics data project using Tinybird

## Install

First install [Tinybird CLI](https://www.tinybird.co/docs/quick-start-cli.html#setting-up-the-cli), you'd need Python 3 installed:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install tinybird-cli
```

Then run the following commands to create all the Data Sources and Pipes and upload some sample data:

```bash
tb auth
tb init --git
```
