# Dorar Translator Bot (Computer Alfelegem Version)

Ke `dorarnet_telegram`, `almunajjid`, na `ArIslamway` channelochi addis
post biseyimeta, wede Amarigna yiteregmal, wede `@ibnuabbas_hara`
yiletefal. Attribution yelem, ye5-15 dekika mekakel new yemikatetu.

**Computer weyis session string AYFELEGEM** -- bot token bicha bemeteqem
public channel preview page (t.me/s/...) eyanebe yiseral.

## Yemiferelgu neger

1. **Ye "Translator Abubeker Abdu" bot token** -- kefit ye Awraq_Alyasmin
   feature lay yeteseterebet bot, yihe token(esu) new yemiwaselew.
   Yihe bot wede @ibnuabbas_hara admin honi message lemelet'af mekemet
   alebet (kefit endeseratew).
2. GitHub account (alesh alu)
3. Railway account (alesh alu)

## Sitegabir - be phone bicha

### 1. Kezih file'och wede GitHub repo mewseded

Ke GitHub app (weyis website) bemeteqem be phone'wo:
- Addis repo mefeter (lemshale `dorar-translator-bot`)
- Yihe file'och sostu (`main.py`, `requirements.txt`, `Procfile`)
  keziya repo wist add/upload maderg

### 2. Railway lay masemat

1. Railway app/website lay "New Project" -> "Deploy from GitHub repo"
   -> ale repo'u yimeret
2. **Variables** tab lay yihen environment variables adergu:
   - `TARGET_BOT_TOKEN` - ye Translator Abubeker Abdu bot token
   - (yasfelgal) `TARGET_CHANNEL` = `@ibnuabbas_hara`
3. Deploy bemadereg bot'u sira yijemral, be5-15 dekika mekakel
   sostu channelochun eyakebe

## Aynkeda/tinat

- Yalefut yeteregem message id `last_seen.json` wist yimezegebal,
  silezih bot'u kedegemo bicha keqedmew sira aymeles.
- T.me/s/ page yemiweta beqemat (limit alebet) - metekakel'u ke 20
  yaneste postoch new yemiasay, silezih bot'u be regelegna
  eyasayew bicha addis'oncun yiketakotal.
