# VScode Lustre extension

This extension provides a syntax highlighting and snippets for LUSTRE language.

## Installation

You can install this extension from the [Open VSX Registry (VSCodium)](https://open-vsx.org/extension/MercierCorentin/lustre) or [VSCode extension store (VSCode)](https://marketplace.visualstudio.com/items?itemName=MercierCorentin.lustre).

Or, if you need development version, you can use these commands:

```bash
sudo apt install npm
npm install -g vsce
git clone https://github.com/MercierCorentin/vscode-lustre.git
cd vscode-lustre
vsce package
```

- Open Visual Studio Code and select View->Extensions from the menu to display the Extensions pane.
- Click the ... at the top-right corner of the Extensions pane and select "Install from VSIX..." on the menu that appears.
- Select the created `.vsix` file.


## Lustre

Lustre is a "synchronous language based on the dataflow model and designed for the description and verification of real-time systems"[1].

This extension implements Lustre Core syntax highlight and snippets. Lustre Core is described in [1].

[1] The Lustre V6 Reference Manual, Erwan Jahier, Pascal Raymond, Nicolas Halbwachs, [http://www-verimag.imag.fr/DIST-TOOLS/SYNCHRONE/lustre-v6/doc/lv6-ref-man.pdf](http://www-verimag.imag.fr/DIST-TOOLS/SYNCHRONE/lustre-v6/doc/lv6-ref-man.pdf)

## Issues

For issues you can either create a Github issue or send an email to the maintainer (corentin.mercier(at)irsn.fr).

## Snippets
| Prefix | Snippet |
|---|---|
| node | Node Header + Body |
| function | Function header + Body |
| node_a | Node Header + Local Variables and Constants declaration +  Body | 
| let    | Body |
| extern_n | External node |
| extern_f | External function |
| var | Variable declaration | 
| const | Constants declaration | 
| type | User type definition | 
| struct | Structure definition | 
| enum | Enum type definition | 
 
