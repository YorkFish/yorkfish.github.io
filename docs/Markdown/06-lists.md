# 6. 列表

## 1. 有序列表

- 用法：`No.` + `.` + `1` 个空格 + 内容
- 说明：有些地方，数字会显示为“英文字母”、“罗马数字”……

### 示例与效果

- 示例

    ```
    1. 有序列表 1
    2. 有序列表 2
    3. ……
    ```

- 效果

    1. 有序列表 1
    2. 有序列表 2
    3. ……

## 2. 无序列表

- 用法：`-` + `1` 个空格 + 内容
- 说明：`-` 可以用 `+` 或者 `*` 代替

### 示例与效果

- 示例

    ```
    - 无序列表 1
    - 无序列表 2
    - ……
    ```

- 效果

    - 无序列表 1
    - 无序列表 2
    - ……

## 3. 列表的层级

### 说明

- “有序列表”与“无序列表”都可以表现层级，或者说是“嵌套”
- 层级可用 `Tab` 实现
- 一般地，`Tab` 的长度为 `4`，可以根据需要改动

### 示例与效果

- 示例

    ```
    - 第一级
        1. 第一项
        2. 第二项
    ```

- 效果

    - 第一级
        1. 第一项
        2. 第二项

## 4. 补充

- 如果，想在行前使用数字，但又不想使用有序列表，可以用反斜杠转义
- 示例

    `4\. 补充`

- 效果

    4\. 补充