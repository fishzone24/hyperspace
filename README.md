# Hyperspace 一键部署脚本

Fork自 [@sdohuajia](https://github.com/sdohuajia)

这是一个用于部署Hyperspace节点的一键脚本，支持以下功能：
- 自动部署Hyperspace节点
- 自动配置模型
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
- 需要确保服务器支持SSE4.1/SSE4.2和AVX指令集
- 建议使用支持AVX2的CPU以获得最佳性能 