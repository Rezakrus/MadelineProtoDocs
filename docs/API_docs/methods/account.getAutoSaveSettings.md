---
title: "account.getAutoSaveSettings"
description: "account.getAutoSaveSettings parameters, return type and example"
grand_parent: "Telegram RPC API"
parent: "Methods"
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/account_getAutoSaveSettings.html
---
# Method: account.getAutoSaveSettings
[Back to methods index](index.html)





### Return type: [account.AutoSaveSettings](/API_docs/types/account.AutoSaveSettings.html)

### Can bots use this method: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$account_AutoSaveSettings = $MadelineProto->account->getAutoSaveSettings();
```

