# Guardian Local Plugin

This is a fork of the `guardian` repo to persist the local version of the Semgrep plugin. The default path is to install the plugin in the `guardian` repo via the Anthropic official marketplace, but if that breaks, this is the backup.

To install the local plugin:
1. Start a Claude Code instance by running:
    ```
    claude
    ```
1. Add the Semgrep marketplace by running the following command in Claude:
    ```
    /plugin marketplace add semgrep/guardian-local
    ```
1. Install the plugin from the marketplace:
    ```
    /plugin install semgrep@semgrep-marketplace
    ```
1. Tell claude to load the plugin:
    ```
    /reload-plugins
    ```
1. Set up the Semgrep plugin by running the following skill. This also installs the Semgrep CLI:
    ```
   /setup-semgrep-plugin
    ```
1. If you run into issues, please reach out in the [Semgrep Community Slack](https://semgrep.slack.com/) and join the #mcp channel.
