---
title: "messages.getWebPage"
description: "Get [instant view](https://instantview.telegram.org) page"
grand_parent: "Telegram RPC API"
parent: "Methods"
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
redirect_from: /API_docs/methods/messages_getWebPage.html
---
# Method: messages.getWebPage
[Back to methods index](index.html)



Get [instant view](https://instantview.telegram.org) page

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|url|[string](/API_docs/types/string.html) | URL of IV page to fetch | Yes|
|hash|Array of [long](/API_docs/types/long.html) |  | Optional|


### Return type: [WebPage](/API_docs/types/WebPage.html)

### Can bots use this method: **NO**


### MadelineProto Example ([now async for huge speed and parallelism!](https://docs.madelineproto.xyz/docs/ASYNC.html)):


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$WebPage = $MadelineProto->messages->getWebPage(url: 'string', hash: [long, long], );
```

