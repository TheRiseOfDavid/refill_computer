# Ubuntu 重灌

## VScode

> 設定檔弄完後，如果沒有生效，就重開 vscode 檢查

- [vscode 全螢幕時，部份地方無法點擊 or 點擊到其他東西，請看 bpasero 留言](https://github.com/microsoft/vscode/issues/170280)

### 字體

- ` "editor.fontFamily"` : `"'Consolas', '微軟正黑體'"`

### 需要網址的內容

- [vscode 使用 微軟正黑體](https://mousyball.github.io/2018/02/12/my-vscode-setting/)
- [vscode 儲存時自動排版](https://blog.csdn.net/qq_43435403/article/details/109071969)

### 必安裝的 extension

- Markdown Preview Enhanced
- Prettier - Code formatter
- Todo Tree
- TODO Highlight
- Bookmarks
- Tabnine
- Code Spell Checker
- Prettier ESLint
- Gitlens
- Git Graph
- Git File History (h logo)
- vscode-imgur
- markdownlint
- clang-format
  - 也需要下載 `sudo apt install clang-format`
  - 在將 path 放入 vscode setting clang-format path
- indent-rainbow

## fisher

[Ubuntu 安裝 Fish Shell + Tide 主題 與各種插件](https://www.kwchang0831.dev/dev-env/ubuntu/fish)

## 安裝套件與指令

```shell
sudo apt-get update
sudo apt-get install gdebi
```

## python

- [安裝 pyenv 以選定特定版本 for specify project](https://github.com/pyenv/pyenv)
- [安裝 virtualenv 以避免 python package 衝突破壞](https://github.com/pypa/virtualenv)
- [pyenv and virtualenv 一起使用的套件](https://github.com/pyenv/pyenv-virtualenv)
  <!-- 不確定是否正確 - `Installing as a pyenv plugin` > `OPTIONAL Add pyenv virtualenv-init to your shell to enable auto-activation of virtualenvs. This is entirely optional but pretty useful. See "Activate virtualenv" below.` 要進行修改
  - 修改如下 `status --is-interactive; and pyenv virtualenv-init - | source` 要改成 `status --is-interactive; and pyenv virtualenv-init --path | source` -->
