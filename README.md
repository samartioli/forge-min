# Minified Version of Forge

<https://github.com/digitalbazaar/forge>

Why? Because forge has a bower component, but it relies on AMD to dynamically load dependencies.

Use this instead in your bower.json

    "dependencies": {
        "forge-min": git@github.com:samartioli/forge-min.git#0.6.21
    },

See this issue: <https://github.com/digitalbazaar/forge/issues/229>

I probably won't be keeping this up to date with forge releases, so feel free to submit pull requests:

    git clone git@github.com:digitalbazaar/forge.git
    cd forge
    git checkout [version]
    cp js/forge.min.js [path/to/forge-min]/forge.min.js
    cd [path/to/forge-min]
    git checkout -b [version]
    git push origin [version]

Then send pull request