# 🧠 Caepe MCP Demo

This repo lets you test our **Caepe MCP server** directly from VS Code using GitHub Copilot Chat.

[![Install Caepe MCP Server](https://img.shields.io/badge/Install%20Caepe%20MCP-%232297E0?logo=visualstudiocode&style=for-the-badge)](vscode:mcp/install?%7B%22name%22%3A%22Caepe%20MCP%20Server%22%2C%22url%22%3A%22https%3A%2F%2Fmcp-dev.biqmind.sh%2Fmcp%2F%22%2C%22headers%22%3A%7B%22organization%22%3A%22biqmind%22%2C%22server-url%22%3A%22dev.biqmind.sh%22%7D%7D)

---

## ✅ Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/) **version 1.100+** with GitHub Copilot Chat enabled  
- [Git CLI](https://git-scm.com/downloads) installed (latest version)
- Access to the `caepe-mcp` server URL

---

## ⚡ How to Use

1. **Clone this repo**:

   ```bash
   git clone https://github.com/biqmind/caepe-mcp-demo.git
   cd caepe-mcp-demo
   ```

2. **Open this folder** in VS Code.

3. **Go to** the `.vscode/mcp.json` file.

4. Click **Start** to connect your MCP server.

5. Open **Copilot Chat** in *agent mode* and try prompting:

   - `#list_clusters`
   - or just type: **“list my clusters”**

   Copilot will call the tool on your MCP server and show the results.

---

## 📂 Project Structure

```
.vscode/
 └── mcp.json   # Defines your MCP server connection
README.md
```

---

✅ **Happy testing!**