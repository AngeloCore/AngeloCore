<h1 align='center'>SRC</h1>
<h2 align='center'>My Projects 😊</h2>
<hr>
<h1 align='center'>discord-reply</h1>
<h3 align='center'>Links:</h3>
<p align='center'>&#8226; NPMjs: https://npmjs.com/package/discord-reply</p>
<h3 align='center'>Example: </h2>

```js

const discord = require('discord.js');
require('discord-reply'); //⚠️ IMPORTANT: put this before your discord.Client()
const client = new discord.Client();

client.on('ready', () => {
  console.log(client.user.tag)
});

client.on('message', async message => {
  if (message.content.startsWith('!reply')) {
    message.lineReply('Hey'); //Line (Inline) Reply with mention

    message.lineReplyNoMention(`My name is ${client.user.username}`); //Line (Inline) Reply without mention
  }
});

client.login('TOKEN');

```
<h3 align='center'>Preview:</h1>
<p align="center"><img src="http://pays.host/uploads/390c2d6f-7281-4ebd-9429-5dbff5bcee44/bAUmaJT0_.png" alt="discord-reply"/>
</p>

<hr>

<h1 align='center'>discord-buttons</h1>
<h3 align='center'>Links:</h3>
<p align='center'>&#8226; NPMjs: https://npmjs.com/package/discord-buttons</p>
<p align='center'>&#8226; Documentation: https://angelocore.gitbook.io/discord-buttons/</p>
<p align='center'>&#8226; Repository: https://github.com/AngeloCore/discord-buttons</p>
<h3 align='center'>Example: </h2>

```js
const discord = require('discord.js');
const client = new discord.Client();
require('discord-buttons')(client);

client.on('ready', () => console.log(client.user.tag));

client.on('message', message => {
    if (message.content.startsWith('!button')) {

        message.buttons('Hello World!', {
            buttons: [
                {
                    style: 'green',
                    label: 'Click to function!',
                    id: 'click_to_function'
                },
                {
                    style: 'url',
                    label: 'Vote for me!',
                    url: 'https://npmjs.com/top.gg-core'
                }
            ]
        })
    }
})

client.login("TOKEN");
```

<h3 align='center'>Preview:</h1>
<p align="center"><img src="https://camo.githubusercontent.com/0a0c8815688e3e6fb17e77e320d88cdae67bcae31a14a9bbd99b6c88912caea6/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3830353430373238353635393935393335362f3833343737393235363737363033323237362f756e6b6e6f776e2e706e67" alt="discord-buttons"/>
</p>

<hr>

<h2 align='center'>BlueAPI.js</h2>
<p align='center'><------------------------------------------------></p>
<p align='center'>Generating meme images!</p>
<p align='center'><------------------------------------------------></p>
<p align="center">
  <a href='https://www.npmjs.com/package/blueapi.js'> NPM.js</a>
</p>

<hr>

<h2 align='center'>And more!...</h2>
<p align="center">&#8226; <a href="https://github.com/AngeloCore">Github</a></p>
<p align="center">&#8226; <a href="https://www.npmjs.com/~angelo2007">NPMjs</a></p>
<p align="center">&#8226; <a href="https://discord.gg/5JtyYqW">Discord Sever</a></p>
<p align="center">&#8226; <a href="" disbaled>Website</a> <small>soon</small></p>
