# TheoTown-translation #
Welcome to the **TheoTown Translation Repository**!
This repository contains the community-maintained translations used by TheoTown. Contributions that improve and maintain existing translations are welcome.

## For translators ##

### How translation works ###
Each `values[.*]/strings.xml` file contains lines like this:
```xml
<string name="tagname">My translation</string>
```
Simply translate the text between the tags (e.g. replace `My Translation` with your translation).

The special symbol `\n` can be used to indicate a new line.

When your changes are done, create a pull request so they can be reviewed and, if appropriate, merged into the main branch.

### Languages ###
Each directory in this repository contains a `strings.xml` file for a specific language.
Here is a list of currently supported languages:
- `values`: English (*default language*) ← **Always up to date**<br/>
- `values-af`: Afrikaans
- `values-ar`: Arabic
- `values-b+fil`: Filipino
- `values-ca`: Catalan
- `values-cs`: Czech
- `values-de`: German ← **Always up to date**
- `values-es`: Spanish
- `values-eu`: Basque
- `values-fa`: Farsi
- `values-fr`: French
- `values-hu`: Hungarian
- `values-id`: Indonesian
- `values-it`: Italian
- `values-ja`: Japanese
- `values-jv`: Javanese
- `values-ko`: Korean
- `values-lt`: Lithuanian
- `values-ms`: Malay
- `values-nl`: Dutch
- `values-pl`: Polish
- `values-pt`: Portuguese
- `values-ru`: Russian
- `values-sk`: Slovak
- `values-sr`: Serbian
- `values-th`: Thai
- `values-tr`: Turkish
- `values-uk`: Ukrainian
- `values-vi`: Vietnamese
- `values-zh-rHK`: Hong Kong Chinese
- `values-zh-rTW`: Traditional Chinese
- `values-zh`: Chinese

The list above reflects the languages currently supported by TheoTown. If you are interested in a language that is not listed, please contact us before starting a translation, as additional languages are only considered on a case-by-case basis.

English and German translations *will always be up to date*.
New strings will be appended to all `strings.xml` files in English by default.

### Escaping characters ###
Certain characters cannot be written directly within the xml file.
You will have to replace them according to the following table:
Character | Escaped form
--|--------------------------
" | `&quot;`
' | `&apos;` or `\'`
< | `&lt;`
\> | `&gt;`
& | `&amp;`

Sidenote:
In [Json based translations](https://forum.theotown.com/viewtopic.php?t=9436) all you have to replace is " by \\".

