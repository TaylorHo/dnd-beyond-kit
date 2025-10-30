<div align="center">
  <a href="https://dnd-beyond-kit.hotay.dev" target="_blank"><img src="https://raw.githubusercontent.com/TaylorHo/dnd-beyond-kit/main/website/dice.svg" width="80" alt="d20 dice" /></a>
  <h1>D&D Beyond Kit</h1>
</div>

- [Website](https://dnd-beyond-kit.hotay.dev)
- [Link for Chrome Web Store](https://chromewebstore.google.com/detail/dd-beyond-kit/gdpopbkamfkkenkillfnocgljokkcopg?utm_source=github)
- [Link for Mozilla Firefox](https://addons.mozilla.org/en-US/firefox/addon/dnd-beyond-kit/?utm_source=github)
- [Translation Tool (Help us translating!)](https://dnd-beyond-kit.hotay.dev/translate)

### This extension is used to:

- Traslate your D&D Beyond character sheet page to your language;
- Use the International Unit System (SI) for metrics on Character Sheet, monsters, spells, etc.;
- Remove the Character Sheep interface pollutionm leaving it simpler;
- Add a "Skip to the top" button on long pages;
- Add autoload on listing pages (such as monsters and spells pages).

---

> [!IMPORTANT]
> Using the character sheet in English is difficult, sometimes, so I've created this extension to simplify the process for non-US citizen users.

### Languages

Currently we have translations to the following languages:

- Brazilian Portuguese (Português)
- Spanish (Español)
- English (Only metric system changes)
- Italian (Italiano)
- French (Français)
- German (Deutsch)
- Czech (Čeština)
- Japanese (日本語)
- Dutch (Nederlands)
- Russian (Русский)
- Traditional Chinese (繁體中文)
- Turkish (Türkçe)
- Korean (한국어)

Want to help us translating D&D Beyond content? We created a [Translation Tool](https://dnd-beyond-kit.hotay.dev/translate) to make this process easier!!

### Contributing

To **edit the current existent translations or to translate more content** from the languages that we currently support, have a look at out [Translation Tool](https://dnd-beyond-kit.hotay.dev/translate).

You can also manually help us translating the content by editing the JSON files located in `translations/` folder.
To do this manually, just add the text you want to edit/translate in lowercase as the **key** of the JSON, and the translate text as the **value** of the JSON.

If you **want to add a new language**, then you can create a new JSON file in the `translations/` folder, with the name lik `<lang>-<country_code>.json`, for example: Brazilian Portuguese is called `pt-br.json`.
in this case we need also to add this configuration to the `popup/popup.html` file and to `manifest.json`. For more details, [open an Issue](https://github.com/TaylorHo/dnd-beyond-kit/issues/new) and we will help you in this process.

For simplicity you can also [add a new language by our web tool, clicking here](https://dnd-beyond-kit.hotay.dev/translate) and clicking in the _"Add new Language"_ button.

### Browser support

Actually we support Firefox and chromium-based browsers, such as Google Chrome, Brave, Opera, and others.
We use the same `manifest.json` for both platforms.

### People who helped translating this extension <3

|  Language                          |  Contributors  |
|------------------------------------|----------------|
|  Brazilian Portuguese (Português)  |  [TaylorHo](https://github.com/taylorho), [San](mailto:pedromussipereira@gmail.com), [susdw](mailto:carloscvgnl@gmail.com) and [Emival Silva](mailto:emival@gmail.com)  |
|  Spanish (Español)                 |  [MrProditio](https://github.com/MrProditio), [Eltrio723](https://github.com/Eltrio723), [Júlia Nogales](mailto:julianolo71@gmail.com), [CookieCrushed](mailto:cookiecrushed18@gmail.com), GhettoMonkey, Hector C. and Serph  |
|  Italian (Italiano)                |  [Gabriele](mailto:we@improve.games), [bembe83](https://github.com/bembe83) and [Il Rich](mailto:il.rich@outlook.com)  |
|  French (Français)                 |  [vgauther](https://github.com/vgauther), [Ins0mniakk](https://github.com/Ins0mniakk), [Saturnin](saturnin@mailibre.fr), [knard](mailto:wotan@knard.be), [savoiet](mailto:savoiet@outlook.com) and Forteleone  |
|  German (Deutsch)                  |  [JulianPrieber](https://github.com/JulianPrieber), [Wilms](mailto:philip.jakob.leopold.wilms@gmail.com), [Catdcast3r](mailto:cardcast3r@gmail.com), [fLowBop](mailto:vincentweber1988@gmail.com), Martin, ash, JRK and Naxras  |
|  Czech (Čeština)                   |  [mlynarp](https://github.com/mlynarp) and Netleak  |
|  Japanese (日本語)                  |  [lill-la](https://github.com/lill-la), [Shun Matsuba](https://x.com/fraulein_trpg), [SaitoJohn](https://github.com/SaitoJohn) and [フロイラ](mailto:matsuba0721.ggl@gmail.com)  |
|  Dutch (Nederlands)                |  [Disispower](https://github.com/Disispower) and Woodychopper  |
|  Russian (Русский)                 |  [MarouchX](mailto:noraundyne@gmail.com)  |
|  Traditional Chinese (繁體中文)     |  anonymous  |
|  Turkish (Türkçe)                  |  [Erozbey](mailto:erozbey1@gmail.com)  |
|  Korean (한국어)                   |  Hwanya  |

### Thanks

If you liked the extension, please give us a star on Github and a good review on [Google Chrome Web Store](https://chromewebstore.google.com/detail/dnd-beyond-kit/gdpopbkamfkkenkillfnocgljokkcopg?utm_source=github).
