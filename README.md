# mineral_codex

[Download the plugin](https://raw.githubusercontent.com/the-byte-bender/mineral_codex/main/mineral_codex.xml)

This here is a database for Lapidary and Ore Minerals found in alteraeon. It's got info on what stats they give and how pure the ores are. This plugin will give you the information automaticly as you prospect and uncover the minerals, so you know what you get before mining it and wasting time.

## Lapidary Minerals

When you uncover a Lapidary Mineral, You'll see text like this before the boring "you uncover..." bit:

```
> primary stat < secondary stat spellcomp? affinity?
```

You got the primary stat that it gives first, shown by the `>` symbol. Then the secondary stat after the `<` symbol.

If it says "spellcomp" after that, that means it has spellcomp.

And the "affinity" part is as the name says. You might not see it if it has none or if the database doesn't have that info about it yet.

For example:

```
> SAVE_FIRE < SAVE_ZAP spellcomp Fire
```

This one primary gives `SAVE_FIRE`, secondary `SAVE_ZAP`, has spellcomp, and has something to do with fire magic.

## Ore Minerals

When you prospect an ore Mineral, You'll see text like this before the boring "you uncover..." bit:

```
ore name purity sign
```

So the name, like "Iron", then a little symbol saying how pure and good it is:

An easy rule to remember for the symbol is that the center is moderately pure, no symbols are shown for that. Then the more greater than signs (`>`) you see, the more pure. The more less than signs (`<`) you see, the worse the purity. So like:

- `>>` most pure
- `>` more pure
- no extra symbols moderately pure
- `<` means less pure
- `<<` is basically junk (least pure)

For example,  `copper>>` means that this will yield copper and its most pure.

That's the gist!

## License

This plugin is licensed under the GPL3 license. That means you can copy, modify, and share this plugin however you want, as long as you share any changes you make under the same GPL3 license.

## Contribute or Suggest Changes

If you find any mistakes or want to add new info to the database, you can help out!

- If you know how to code, submit a pull request with your changes.
- If you don't know how to code, just mudmail Sylva with what you want to change, and I'll take care of it.

## A Kind Word Goes a Long Way

If you like my work on this plugin, a kind word mudmailed to me would truly make my day! Even just a simple "thanks" means a lot, suggestions are also very appreciated! You don't need to give me anything else, but if you really want to, you could also send a little gold my way. Either way is perfectly fine, and even nothing at all is totally okay too! Just knowing my work is appreciated is more than enough for me.
