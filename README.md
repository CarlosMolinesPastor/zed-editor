# ZED EDITOR CONFIG

ZED EDITOR is a modern code editor that is fast, lightweight, and designed for collaboration. It is built on top of the Monaco Editor and provides a rich set of features for developers.

Zed editor's configuration to make it more productive. With copilot in prediction mode, vim shortcuts and more

To install the settings in gnu/linux:

First of all install zed editor from <https://zed.dev/>

Then, you need to create the `~/.config/zed` directory if it doesn't exist:

```bash
mkdir ~/.config/zed
```

Then, you can run the following commands in your terminal:

```bash
cd ~/
git clone https://github.com/CarlosMolinesPastor/zed-editor.git
cd zed-editor/
cp -r settings.json ~/.config/zed/settings.json
```
