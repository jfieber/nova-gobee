# Go-By&trade; - Go Extension for Nova

---

**Go-By** (pronounced "go-bee", like the fish) provides rich support for Go development in Nova via the _gopls_ language server, and fast syntactic analysis thanks to [Tree-sitter][3].

If you have installed our [C][4] extension, this extension is a complete
superset and you can use this instead.

This extension requires Nova 10.0 or better, and because of at least one fixed bug, we
highly recommend updating to Nova 10.4 or better.

## ✨ Features ✨

- Syntax Highlighting
- Indentation (automatic, somewhat limited)
- Symbols
- Code Folding
- **REST ARE TODO**
- Format Selection or File, including On Save
- Jump to Definition, Declaration, Implementation, Type Definition
- Find References
- Find Symbol
- Rename Symbol
- Hover Tooltips
- Signature Assistance
- Code Quality Hints
- Code Actions

## 📸 Screenshots 📸

![](https://raw.githubusercontent.com/staysail/nova-cdragon/main/screenshot1.png)
![](https://raw.githubusercontent.com/staysail/nova-cdragon/main/screenshot2.png)
![](https://raw.githubusercontent.com/staysail/nova-cdragon/main/screenshot3.png)
![](https://raw.githubusercontent.com/staysail/nova-cdragon/main/screenshot4.png)

## Why Another Go Extension?

There are at least three other extensions providing support for Go for Nova.

Our intention in this extension is to provider faster and more accurate syntax
highlighting by using the Tree-Sitter support in Nova 10 and later.

Furthermore, we believe we can leverage the work we have done for other C
family languages in our C-Dragon and D-Velop extensions to quickly bring a richer
set of capabilities to Nova than the other extensions currently offer.
We think this is probably _easier_ than submitting PRs to those other extensions,
especially as our use of Tree-sitter is a fairly big departure from the way
the other ones work.

## ⚙️ Language Server Integration ⚙️

TBD.

## 🛡️ Security Considerations 🛡️

TBD.

## 🔮 Future Directions 🔮

TBD.

Tasks to build using go.

Better support for go modules.

Debugging via delve.

## 🐜 Bugs 🐜

- WE ARE JUST STARTING OUT. Expect problems.

- Symbol renames can mess up highlighting. Make a subsequent change to refresh the
  tree-sitter grammar's view of things. This appears to be a Nova defect.

- Some things that should be code actions are not.

## 🌐 Localizations 🌐

If you'd like to help with localizing this extension, please submit an issue or
contact us directly. We have designed the extension to make this a very easy task
for anyone able to perform the actual translations.

## ⚖️ Legal Notices ⚖️

Go-By&trade; is a trademark of Staysail Systems, Inc.

Copyright &copy; 2022 Staysail Systems, Inc.

This extension is made available under the terms of the [MIT License][8].

Some of the code in this extension was adapted from [Cameron Little][6]'s
excellent [TypeScript extension][7] for Nova.
That extension is also licensed under the MIT license and carries the
following copyright notice:

> Copyright (c) 2020 Cameron Little

This work has some code from [Ben Beshara][1]'s original [C++ ClangD extension][2].
That extension carried the following license declaration in its manifest (which
we have preserved):

> "license": "MIT",

[3]: https://tree-sitter.github.io/tree-sitter/ "Tree-sitter web site"
[4]: https://github.com/staysail/nova-c "Tree-sitter grammar for C"
[5]: https://brew.sh "Homebrew package manager"
[6]: https://github.com/apexskier "Cameron Little's GitHub page"
[7]: https://github.com/apexskier/nova-typescript "TypeScript Extension for Nova"
[8]: https://github.com/staysail/nova-cdragon/blob/main/LICENSE.md "MIT License"
