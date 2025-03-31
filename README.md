# Hyperspace 一键部署脚本

Fork自 [@sdohuajia](https://github.com/sdohuajia)

这是一个用于部署Hyperspace节点的一键脚本，支持以下功能：
- 自动部署Hyperspace节点
- 自动配置模型（自动尝试多个模型版本）
- 支持日志监控
- 支持积分监控
- 支持节点管理

## 一键安装命令

```bash
wget -O hyperspace.sh https://raw.githubusercontent.com/fishzone24/hyperspace/main/hyperspace.sh && chmod +x hyperspace.sh && ./hyperspace.sh
```

## 使用说明

1. 运行上述一键安装命令
2. 按照脚本提示进行操作
3. 输入您的私钥
4. 选择节点等级
5. 等待部署完成

## 注意事项

- 本脚本适用于Ubuntu系统
- CPU要求：
  - 最低要求：支持SSE4.1/SSE4.2和AVX指令集
  - 推荐配置：支持AVX2指令集的CPU（如Intel Xeon E5 v3/v4系列或更新）
  - 已知不兼容：Intel Xeon E5 v2系列CPU可能无法正常运行
- 脚本会自动尝试多个模型版本，以寻找兼容的版本
- 如果所有模型版本都失败，请检查CPU兼容性或联系支持
- 建议使用支持AVX2的服务器以获得最佳性能 