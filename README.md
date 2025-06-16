To install the 'Addition' MCP server, run the following command:

'''json
{
"mcpServers":{
        "Addition": {
            "command": "uvx",
            "args": [
                "--from",
                "git+https://github.com/Shivangi-Arul/mcpserverexample.git",
                "mcp-server"
                    ]
        }
    }
}
'''

This will fetch and install the mcp-server tool from your GitHub repository using the UVX package manager.