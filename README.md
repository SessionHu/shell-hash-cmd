# Shell Hash CMD

- 调用Windows组件在右键菜单中快速计算文件HASH值

## 原理

- 通过添加注册表项使文件上下文菜单中出现 `计算HASH值` 选项

- 计算直接使用 `%windir%\System32\certutil.exe` 的 `-hashfile` 参数进行计算

## 使用

- 打开 `calc-hash.reg` 合并到注册表

- 您将可以在文件的上下文菜单中看到 `计算HASH值` 的折叠菜单里进行计算了

- 由于需要使用 `cmd.exe` 显示信息，会造成一定程度的延迟

## 许可证

- 本项目使用 `CC-BY-SA-4.0` 许可证进行传播
