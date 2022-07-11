# composer

```
composer require zen-studio/line-formatter
```

#Config
默认最大深度调整为20层，可在config文件里自定义日志josn的最大深度

config/autoload/logger.php
```
'formatter' => [
            'constructor' => [
                'maxNormalizeDepth' => 20,
            ],
        ],
```
