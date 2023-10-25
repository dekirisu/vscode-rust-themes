
<p align="center"><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/78398528/277899465-be329017-5843-4110-887f-8487b2eb4883.gif"></p>
<p align="center">
<a href="https://github.com/dekirisu/vscode-rust-themes" style="position:relative">
        <img src="https://img.shields.io/badge/github-f62ca5?logo=github">
    </a>&nbsp;
    <a href="https://discord.gg/kevWvBuPFg" style="position:relative">
        <img src="https://img.shields.io/badge/discord-ae5cbd?logo=discord&logoColor=white">
    </a>&nbsp;
    <a href="https://mastodon.social/@dekirisu" style="position:relative">
        <img src="https://img.shields.io/badge/mastodon-787fd0?logo=mastodon&logoColor=white">
    </a>&nbsp;
    <a href="https://twitter.com/dekirisu" style="position:relative">
        <img src="https://img.shields.io/badge/twitter-2bb2ea?logo=x&logoColor=white">
    </a>
</p>

The themes are mainly meant for the Rust language! It uses textmate scopes as base and LSP semantic tokens on top.<br>

## 🦊 Settings
For the themes to work as intended, `rust-analyzer` has to be installed and the following setting appended into your VSCodes `settings.json` (or enabled using the ui):
```json
"rust-analyzer.semanticHighlighting.punctuation.enable": true,
```
I personally dislike bracket pair colorization, instead I've enabled guides, while the brackets are always the same color - `settings.json`:
```json
"editor.bracketPairColorization.enabled": false,
"editor.guides.bracketPairs": "active",
```
The slight horizontal lines are created with [alefragnani.separators](https://marketplace.visualstudio.com/items?itemName=alefragnani.separators) and these settings:
```json
"separators.classes.borderWidth": 0,
"separators.constructors.borderWidth": 0,
"separators.enums.borderWidth": 0,
"separators.interfaces.borderWidth": 0,
"separators.namespaces.borderWidth": 0,
"separators.structs.borderWidth": 0,
"separators.methods.borderWidth": 2,
"separators.functions.borderWidth": 2,
"separators.functions.borderStyle": "dashed",
"separators.methods.borderStyle": "dashed",
"separators.location": "belowTheSymbol",
```
### 🌆 Theme "Dawn"
<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/78398528/277901185-989ff12c-da29-4816-9f41-5873dba6ec5a.png">

### 🌈 Theme "Rainbow"
<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/78398528/277901200-4900782d-a454-4593-89dd-af657f2f5ce1.png">

### 🌌 Theme "Entropy"
<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/78398528/277901197-8d32ddc8-138b-4b6d-82c9-0a39026d2ddd.png">