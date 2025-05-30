
Self: https://github.com/palladius/ai-friendly-agents/ (public)

## Breaking changes

Currently some agents are broken. I've added a dangerous change.

However, a stable version is available here: https://github.com/palladius/ai-friendly-agents/tree/v0.9/

# AI friendly agents

A bunch of friendly agents ready to use with ADK, MCP, A2A et al.

Dir structure:

* `adk-prod-agents/`: agents built with ADK. Production ready, ready to use.
* `adk-test-agents/`: agents built with ADK. More to learn how to do things. Could be cut and paste of public docs.
* `samples/`: end-to-end samples by the author.

Better samples can be found here: https://github.com/google/adk-samples

# Install

```bash
# 1. Clone and adapt env file
git clone https://github.com/palladius/ai-friendly-agents/
cp .env.dist .env
# edit away .env with your info

# 2. Install virtualenvenv
python -m venv .venv
source .venv/bin/activate

# 3.
cd adk-prod-agents/
pip install -r requirements.txt
```

