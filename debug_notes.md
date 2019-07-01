## 问题记录

### `easydict` 的问题

遇到一些奇怪的问题, 发现是在服务器上 `easydict` 使用有问题 (`CFG.TRAIN.LR` 这种多层应用失败，非要 `CFG.TRAIN['LR']` 才能成功), 导致 `yml` 配置文件里面的配置用不上。

### `nn.parallel.data_parallel` 的问题

报错说没有 `parameters` 方法，可能是版本问题。
改成不用并行执行。

