# VScode Lustre extension

This extension provides a syntax highlighting and snippets for LUSTRE language.

## Installation

This extension is being built. To use it, open a terminal and type:
```bash
sudo apt install npm
npm install -g vsce
git pull https://github.com/MercierCorentin/vscode-lustre.git
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

## Versions
| Number  |  Release Date  | Changes  |
|---|---|---|
| 0.1.0  | Within a few days  |  Syntax highlight + Snippets |
| 1.0.0  | Within the next few weeks  |  Stable version |
