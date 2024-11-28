# TheoTown-translation #
Welcome to the **TheoTown Translation Repository**!
This is where the community can contribute to localizing TheoTown into various languages.
Your help makes TheoTown more accessible to players around the globe.


## For translators ##

### How translation works ###
Each `values[.*]/strings.xml` file contains lines like this:
```xml
<string name="tagname">My translation</string>
```
Simply translate the text between the tags (e.g. replace `My Translation` with your translation).

The special symbol `\n` can be used to indicate a new line.

When your translation is done, **make sure to create a 'pull request'** so it can be merged to main branch.
If you forget to do that step your translation won't be added to the project!

### Languages ###
Each directory in this repository contains a `strings.xml` file for a specific language.
Here is a list of currently supported languages:
- `values`: English (*default language*) ← **Always up to date**<br/>
- `alues-af`: Afrikaans
- `alues-b+fil`: Filipino
- `alues-ca`: Catalan
- `alues-cs`: Czech
- `alues-de`: German ← **Always up to date**
- `alues-es`: Spanish
- `alues-eu`: Basque
- `alues-fr`: French
- `alues-hu`: Hungary
- `alues-in`: Indonesian
- `alues-it`: Italian
- `alues-ja`: Japanese
- `alues-ko`: Korean
- `alues-lt`: Lithuanian
- `alues-ms`: Malay
- `alues-nl`: Dutch
- `alues-pl`: Polish
- `alues-pt`: Portuguese
- `alues-ru`: Russian
- `alues-sk`: Slovak
- `alues-sr`: Serbian
- `alues-th`: Thai
- `alues-tr`: Turkish
- `alues-uk`: Ukrainian
- `alues-vi`: Vietnamese
- `alues-zh-rHK`: Hong Kong Chinese
- `alues-zh-rTW`: Traditional Chinese
- `alues-zh`: Chinese

If you'd like to add a new language, refer to the [ISO 639-1](http://www.loc.gov/standards/iso639-2/php/code_list.php) two-letter language codes and create a corresponding directory.

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



## For developers ##
### Grab script ###
There's a `grab.sh` script included that can be used to grab current translations files from the project directory automatically (developer only). For that to work you have to setup a local TheoTown symbolic link to your TheoTown project directory. To do this, execute a command like the following (here assuming running WSL):
```sh
ln -s /mnt/c/Users/User/StudioProjects/TheoTown66 TheoTown
```
