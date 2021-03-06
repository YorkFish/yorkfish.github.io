# Vintageous

## 1. 安装

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>p</kbd> > `Install Package` > `Vintageous`

## 2. 配置

1. `Preferences` > `Settings`
2. 添加如下语句

    ```json
    // If true, debug information will be printed to the console.
    "vintageous_verbose": false,
    
    // If true, some key bindings prefaced by the CTRL modifier will override default Sublime Text
    // key bindings.
    "vintageous_use_ctrl_keys": false,
    
    // If true, search occurrences will be highlighted in '/', '?', etc.
    // (Disabled.)
    "vintageous_hlsearch": true,
    
    // If true, search patterns will be applied incrementally as they are typed in.
    // (Disabled.)
    "vintageous_incsearch": true,
    
    // If true, ':' and ex commands will be available.
    "vintageous_enable_cmdline_mode": true,
    
    // If true, the current mode will be reset to normal mode when a tab gets activated.
    "vintageous_reset_mode_when_switching_tabs": true,  // I changed with 'false'
    
    // If true, some commands will take the current indentation level into account.
    // (Disabled.)
    "vintageous_autoindent": true,
    
    // If true, copy actions will always propagate to the system clipboard.
    "vintageous_use_sys_clipboard": false,
    
    // If true, / and ? will use regular expressions.
    // If false, smart case will be used instead: the pattern will be interpreted literally and, if
    // it's either all lowercase or all uppercase, case will be ignored too.
    "vintageous_magic": true,
    
    // If true, /, ?, * and # will always ignore case.
    "vintageous_ignorecase": true,
    
    // Logging level. Used for diagnostics and troubleshooting. Common valid
    // values are 'debug', 'info', 'error', 'critical'. Most users should
    // not need to modify the default value.
    "vintageous_log_level": "error"
    ```

3. 保存、退出
