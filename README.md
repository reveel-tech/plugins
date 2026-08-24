# Reveel for AI

Bring your Reveel workspace into your AI assistant. Create, improve, translate, and organize guides and content with natural language.

## Install Reveel

Marketplace installation is recommended. It includes Reveel’s built-in guidance as well as the connection to your workspace.

<details>
<summary><strong>Claude</strong></summary>

1. Open **Settings** in the Claude app and select **Plugins**.
2. Select **Add** in the top-right corner, then choose **Add Marketplace**.
3. Select **Add from a repository**.
4. Enter `https://github.com/reveel-tech/plugins` and select **Sync**.
5. When **Reveel** appears, open it and select **Install**.

<details>
<summary>Command alternative</summary>

```text
/plugin marketplace add reveel-tech/plugins
/plugin install reveel@reveel
```

</details>

</details>

<details>
<summary><strong>ChatGPT desktop</strong></summary>

1. Open the **Plugins** tab in ChatGPT desktop.
2. Select **Manage**, then choose **Add Marketplace**.
3. Add `https://github.com/reveel-tech/plugins` as a repository marketplace.
4. Open the **Reveel** marketplace and select the Reveel plugin.
5. Review the plugin and select the plus button to install it.
6. Connect your Reveel account when prompted, then start a new chat.

After installation, start a new Work or Codex chat to use Reveel.

<details>
<summary>Command alternative</summary>

```bash
codex plugin marketplace add reveel-tech/plugins
codex plugin add reveel@reveel
```

To refresh the marketplace later:

```bash
codex plugin marketplace upgrade reveel
```

</details>

</details>

## Other ways to connect

<details>
<summary><strong>Gemini CLI</strong></summary>

Install Reveel as an extension:

```text
gemini extensions install https://github.com/reveel-tech/plugins
```

</details>

<details>
<summary><strong>An MCP-compatible desktop or web app</strong></summary>

If your assistant supports remote MCP servers, open its MCP, Integrations, or Connectors settings and add a remote server with this URL:

```text
https://server.eu-central-1.reveel.guide/mcp
```

Complete the assistant’s sign-in flow when prompted. Direct MCP connections provide Reveel tools; marketplace installs are recommended when available because they also include Reveel’s built-in guidance.

</details>

## Sign-in and permissions

Reveel uses your assistant’s secure sign-in flow. You will be asked to authorize access before your assistant can view or change workspace content.

Your assistant only performs actions available to the Reveel account and workspace you authorize. Review requested actions carefully, especially when changing or publishing content.

## Need help?

For help with Reveel or account access, visit [reveel.fi](https://reveel.fi) or contact [support@reveel.guide](mailto:support@reveel.guide).

Reveel’s terms and privacy information are available at [reveel.fi](https://reveel.fi).
