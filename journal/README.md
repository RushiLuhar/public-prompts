# Purpose 
The journal prompt is intended to be used as the Custom Instructions for a Claude Project that acts as a useful journal. The prompts takes a user’s input and converts it into a journal entry with metadata stored in the frontmatter of each post. 


## GitHub integration
If a new journal entry is created using Claude desktop and if the [GitHub MCP Server](https://github.com/modelcontextprotocol/servers) is available, the prompt will push the journal entry to the repository associated with the journal. If you don’t want to use GitHub feel free to ignore the section. Without the MCP server installed, the prompt will not do anything. 