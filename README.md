# Cursor Setup

This is probably the same setup approach as for VS Code.

1. Install the silver searcher (ag). If you use nix:

   ```
   nix-env -i silver-searcher
   ```

2. If you have a directory with markdown notes, as for Obsidian, Emacs Deft,
   or using my .vim repo, link to it for the VS Code Wiki plugin:

   ```
   ln -s ~/.deft ~/vscode_wiki
   ```

3. Before installing Cursor IDE, clone this repo:

   ```
   git clone https://github.com/wschroeder/vscode-config /Users/$USER/Library/Application Support/Cursor
   ```

4. Install Cursor IDE.

5. Open Cursor IDE, and install these plugins:

   * Vim by vscodevim
   * Nix Environment Selector by arrterian
   * Run on Save by emeraldwalk
   * ElixirLS: Elixir support and debugger by JakeBecker
   * VS Code Wiki by Yunseok

6. Profit!

