# 给 AI 的上下文（重要）

## AI 训练数据里大量是 Reactive 旧写法。让 AI 写代码前，先给它这段话：

我在用 Reactive Network 的 Omni 新版本（2026-10-28 主网迁移后）。请只参考 https://dev.reactive.network/reactive-contracts 、https://dev.reactive.network/callback-contracts 、https://dev.reactive.network/economy 和 https://github.com/Reactive-Network/reactive-smart-contract-demos/tree/omni/src/micro-demos 。不要使用 vm 修饰符、ReactVM、emit Callback 或系统合约 0x...fffFfF（只有 Cron 事件来自它）。react() 必须加 onlySystem，回调用 requestCallbackV_1_0。
