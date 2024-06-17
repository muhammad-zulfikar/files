### How can I add it to my repo?

1.  Copy [index.html](https://github.com/brianjenkins94/private-repo-file-explorer/blob/main/index.html) to your [GitHub Pages source folder](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
2.  Create a `tree.txt`:

    ```bash
    find . -type f -not -path "*/.*" -not -path "*/node_modules/**" > tree.txt
    ```

    The files listed in `tree.txt` will be navigable through the file explorer.

That's it!

### License

`private-repo-file-explorer` is licensed under the [MIT License](https://github.com/brianjenkins94/private-repo-file-explorer/blob/main/LICENSE).

All files located in the `node_modules` directory are externally maintained libraries used by this software which have their own licenses; it is recommend that you read them, as their terms may differ from the terms in the MIT License.
