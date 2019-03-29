---
title: messages.getPinnedDialogs
description: Get pinned dialogs
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: messages.getPinnedDialogs  
[Back to methods index](index.md)


Get pinned dialogs



### Return type: [messages\_PeerDialogs](../types/messages_PeerDialogs.md)

### Can bots use this method: **NO**


### MadelineProto Example:


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
define('MADELINE_BRANCH', '');
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$messages_PeerDialogs = $MadelineProto->messages->getPinnedDialogs();
```

Or, if you're into Lua:

```lua
messages_PeerDialogs = messages.getPinnedDialogs({})
```
