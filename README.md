### How can I add it to my repo?

1.  Copy [index.html](https://github.com/muhammad-zulfikar/files/blob/main/index.html) to your [GitHub Pages source folder](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
2.  Create a `tree.txt`:

    ```bash
    find . -type f -not -path "*/.*" -not -path "*/node_modules/**" | sort > tree.txt
    ```

    The files listed in `tree.txt` will be navigable through the file explorer.

That's it!