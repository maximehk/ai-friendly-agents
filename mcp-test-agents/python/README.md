Copying C/S for python from here:
* https://github.com/modelcontextprotocol/quickstart-resources/tree/main/weather-server-python

I don't personally understand why Anthropic defaults to STDIO, with SSE I can host and see all servers very easily.

## Libraries for Python MCP

* ? https://github.com/jlowin/fastmcp (10k 🌟 !) Haven't tested it yet, but look at the stars! [pypi](https://pypi.org/project/fastmcp/)

## Transport

MCP uses JSON-RPC 2.0 as its wire format.

Seems like SSE default port is `8000`: http://localhost:8000/sse

There are 3 forms of transport (poorly defined in [official docs](https://modelcontextprotocol.io/docs/concepts/transports#built-in-transport-types) which only explains 2):

* **STDIO** (stdin/out - no socket is used).
* **SSE** (network)
* **Streamable HTTP** (network).
