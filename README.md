![](https://github.com/tofrankie/blog/raw/main/images/cover.png)

Personal collection of [Raycast](https://www.raycast.com/?via=73820f) extensions.

## Published Extensions

| Extension             | Description                                                                           | Install                                                                                          |
| :-------------------- | :------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------- |
| WeChat DevTool        | Quickly open WeChat mini program project via official CLI                             | [Install from Raycast Store](https://www.raycast.com/tofrankie/wechat-devtool?via=73820f)        |
| Atlassian Data Center | Search and manage Confluence contents and Jira issues                                 | [Install from Raycast Store](https://www.raycast.com/tofrankie/atlassian-data-center?via=73820f) |
| Chinese Converter     | Convert number input into Chinese formatted text, including uppercase RMB amount text | [Install from Raycast Store](https://www.raycast.com/tofrankie/chinese-converter?via=73820f)     |

Find more published extensions on the [Raycast Profile](https://www.raycast.com/tofrankie?via=73820f).

## Unpublished Extensions

| Extension                                       | Description                     |
| :---------------------------------------------- | :------------------------------ |
| [GitHub Navigator](extensions/github-navigator) | Browse your GitHub repositories |

To install an unpublished extension locally, clone this repository and run the following commands:

```bash
# Clone the repository
git clone https://github.com/tofrankie/raycast-collection.git
cd raycast-collection

# Install dependencies for a single workspace
npm install --workspace=github-navigator

# Start development mode and install the extension in Raycast
npm run dev --workspace=github-navigator

# Optionally verify the production build
npm run build --workspace=github-navigator
```

Replace `github-navigator` with another workspace name to install a different extension.

## Resources

- [Raycast Store](https://www.raycast.com/store?via=73820f)
- [Raycast Developer Documentation](https://developers.raycast.com/?via=73820f)
- [Raycast Extensions Repository](https://github.com/raycast/extensions)
- [如何开发一个 Raycast 扩展？](https://github.com/tofrankie/blog/issues/364)
- [当 Raycast extensions 仓库过大，如何更方便提交 PR？](https://github.com/tofrankie/blog/issues/391)

## License

MIT License © [Frankie](https://github.com/tofrankie)
