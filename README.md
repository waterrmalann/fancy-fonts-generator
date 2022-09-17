# 💬 𝕱𝖆𝖓𝖈𝖞 𝕱𝖔𝖓𝖙𝖘 𝕲𝖊𝖓𝖊𝖗𝖆𝖙𝖔𝖗

A super-simple web app that you can use to generate cool, weird, and beautiful text using pseudofonts made with Unicode characters. This is the GUI-based equivalent of the [Fancy Fonts Bot](https://github.com/waterrmalann/telegram-fancy-fonts-bot) for Telegram that I wrote not too long ago. They are both similar in terms of functionality and the font system is cross-compatible.

**Note:** Text generated using this application may not always be readable, they could also cause accessibility issues as screen-readers might not recognize them. So it is advised that you use them knowing the downsides.*

> 𝕿𝖍𝖎𝖘 𝖕𝖆𝖗𝖆𝖌𝖗𝖆𝖕𝖍 𝖔𝖋 𝖙𝖊𝖝𝖙 𝖜𝖆𝖘 𝖌𝖊𝖓𝖊𝖗𝖆𝖙𝖊𝖉 𝖚𝖘𝖎𝖓𝖌 𝖙𝖍𝖊 𝖜𝖊𝖇 𝖆𝖕𝖕.
> 
> 𝓘𝓽 𝓾𝓼𝓮𝓼 𝓼𝓸𝓶𝓮 𝓸𝓯 𝓽𝓱𝓮 𝓭𝓲𝓯𝓯𝓮𝓻𝓮𝓷𝓽 𝓯𝓸𝓷𝓽𝓼 𝓽𝓱𝓪𝓽 𝓪𝓻𝓮 𝓪𝓿𝓪𝓲𝓵𝓪𝓫𝓵𝓮 𝓫𝔂 𝓭𝓮𝓯𝓪𝓾𝓵𝓽.
> 
> 𝕋𝕙𝕚𝕤 𝕜𝕚𝕟𝕕 𝕠𝕗 𝕥𝕖𝕩𝕥 𝕔𝕒𝕟 𝕓𝕖 𝕔𝕠𝕡𝕚𝕖𝕕 𝕒𝕟𝕕 𝕡𝕒𝕤𝕥𝕖𝕕 𝕒𝕟𝕪𝕨𝕙𝕖𝕣𝕖.
> 
> 𝑻𝒉𝒆𝒚 𝒘𝒊𝒍𝒍 𝒔𝒕𝒊𝒍𝒍 𝒓𝒆𝒕𝒂𝒊𝒏 𝒕𝒉𝒆𝒊𝒓 𝒐𝒓𝒊𝒈𝒊𝒏𝒂𝒍 𝒍𝒐𝒐𝒌 𝒂𝒔 𝒍𝒐𝒏𝒈 𝒂𝒔 𝒕𝒉𝒆 𝒑𝒍𝒂𝒕𝒇𝒐𝒓𝒎 𝒔𝒖𝒑𝒑𝒐𝒓𝒕𝒔 𝒖𝒏𝒊𝒄𝒐𝒅𝒆.
> 
> 𝚃𝚑𝚎𝚢 𝚖𝚒𝚐𝚑𝚝 𝚜𝚘𝚖𝚎𝚝𝚒𝚖𝚎𝚜 𝚋𝚎 𝚍𝚒𝚏𝚏𝚒𝚌𝚞𝚕𝚝 𝚝𝚘 𝚛𝚎𝚊𝚍 𝚑𝚘𝚠𝚎𝚟𝚎𝚛, 𝚊𝚗𝚍 𝚌𝚊𝚞𝚜𝚎 𝚊𝚌𝚌𝚎𝚜𝚜𝚒𝚋𝚒𝚕𝚒𝚝𝚢 𝚒𝚜𝚜𝚞𝚎𝚜.
> 
> Ｓｏ Ｉ'ｄ ｒｅｃｏｍｍｅｎｄ ｎｏｔ ｕｓｉｎｇ ｉｔ ｆｏｒ ｉｍｐｏｒｔａｎｔ ｔｅｘｔ.
> 
> 🅞🅝🅛🅨 🅤🅢🅔 🅘🅣 🅣🅞 🅗🅐🅥🅔 🅕🅤🅝!

#### Features

- Real-time text to pseudofont conversion.
- 27 unique fonts pre-defined. Easy to add more thanks to the simple system.
- Can double as a pun generator. 😛
- Ability to convert all available fonts at the same time.

#### To-Do

- More fonts.
- Improve the UI and make it look better.
- Make the psuedofont class more advanced to support custom symbols and replacements with more than 1 character. (eg: "V" to "\\/")

## 🚀 Getting Started

### Live Version

A live version of the fonts generator is available [here](https://waterrmalann.github.io/fancy-fonts-generator). If you however want to host your own version of the app, follow the steps down below to get started.

### Hosting locally

1. [Clone the repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
```
git clone https://github.com/waterrmalann/fancy-fonts-generator.git
```
2. Install the dependencies.
```
npm install
```
3. This will start a live server. Head to the IP shown in the console.
```
npm run serve
```

### Adding new fonts

The fun stuff! Fonts are stored in a json file in the root directory with the name `fonts.json`. Each font is stored in this format:

```json
{
    "fontName": "FullWidth",
    "fontLower": "ａｂｃｄｅｆｇｈｉｊｋｌｍｎｏｐｑｒｓｔｕｖｗｘｙｚ",
    "fontUpper": "ＡＢＣＤＥＦＧＨＩＪＫＬＭＮＯＰＱＲＳＴＵＶＷＸＹＺ",
    "fontDigits": "０１２３４５６７８９"
}
```

Leave an empty string for empty parameters. It will default to english letters and numbers.

- **fontName**: The name of the font.
- **fontUpper**: Uppercase letters of that font. (Can be a string or an array of length 26)
- **fontLower**: Lowercase letters of that font. (Can be a string or an array of length 26)
- **fontDigits**: Numbers of that font. (Can be a string or an array of length 10)

Note: **fontLower** and **fontUpper** must always be 26 characters. **fontDigits** must always be 10 characters. The pseudofont class currently isn't failsafe. Foolproofing it is on my todo list.

## 🤝 Contributing

Contributions are accepted and there really isn't any strict rules. Feel free to open a pull request to fix any issues or to make improvements you think that should be made. You can also add new fonts to the font database or help me with the to-do list above. Any contribution will be accepted as long as it doesn't stray too much from the objective of the app. If you're in doubt about whether the PR would be accepted or not, you can always open an issue to get my opinion on it.

License
----

MIT License, see [LICENSE](LICENSE)
