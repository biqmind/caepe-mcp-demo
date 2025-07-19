# 🧠 Caepe MCP Demo

This repo lets you test our **Caepe MCP server** directly from VS Code using GitHub Copilot Chat.

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

## 🌐 Option 2: Install via Browser 

You can also install the MCP server directly by visiting:

👉 [https://mcp-dev.biqmind.sh/](https://mcp-dev.biqmind.sh/)

Follow the instructions on the page to register the Caepe MCP Dev server into VS Code.

## 📂 Project Structure

```
.vscode/
 └── mcp.json   # Defines your MCP server connection
README.md
```

---

✅ **Happy testing!**