## Fontbakery report

Fontbakery version: 0.5.2.dev76+g2b6adfed

<details>
<summary><b>[6] Orbitron-Roman-VF.ttf</b></summary>
<details>
<summary>:fire: <b>FAIL:</b> METADATA.pb font.filename and font.post_script_name fields have equivalent values?</summary>

* [com.google.fonts/check/097](https://github.com/googlefonts/fontbakery/search?q=com.google.fonts/check/097)
* :fire: **FAIL** METADATA.pb font filename="Orbitron-Roman-VF.ttf" does not match post_script_name="Orbitron-Regular".

</details>
<details>
<summary>:fire: <b>FAIL:</b> METADATA.pb: Filename is set canonically?</summary>

* [com.google.fonts/check/105](https://github.com/googlefonts/fontbakery/search?q=com.google.fonts/check/105)
* :fire: **FAIL** METADATA.pb: filename field ("Orbitron-Roman-VF.ttf") does not match canonical name "Orbitron-Regular.ttf".

</details>
<details>
<summary>:fire: <b>FAIL:</b> Checking with Microsoft Font Validator.</summary>

* [com.google.fonts/check/037](https://github.com/googlefonts/fontbakery/search?q=com.google.fonts/check/037)
* :fire: **FAIL** MS-FonVal: The device table StartSize is greater than the end size DETAILS: LookupList, Lookup[0], SubTable[0](PairPos, fmt 1), PairSet[5], PairValueRecord[4], Value1, XAdvDeviceTable
* :warning: **WARN** MS-FonVal: The version number is valid, but less than 5 DETAILS: 4
* :warning: **WARN** MS-FonVal: PANOSE(tm) is undefined. Font mapping may not work properly
* :warning: **WARN** MS-FonVal: There are undefined bits set in fsSelection field DETAILS: Bit(s) 7
* :warning: **WARN** MS-FonVal: A CodePage bit is set in ulCodePageRange, but the font is missing some of the printable characters from that codepage DETAILS: bit #0, Latin 1 (38 missing, first ten missing chars are: U005E U201A U0192 U201E U2020 U2021 U2030 U2039 U2122 U203A)
* :warning: **WARN** MS-FonVal: The table does not contain any Apple subtables
* :warning: **WARN** MS-FonVal: Apple logo mapping test not performed, cmap 1,0 not present
* :warning: **WARN** MS-FonVal: Characters are mapped in the Unicode Private Use area
* :warning: **WARN** MS-FonVal: Duplicated knots DETAILS: Glyph index 232
* :warning: **WARN** MS-FonVal: The unitsPerEm value is not a power of two DETAILS: 1000
* :warning: **WARN** MS-FonVal: The lowestRecPPEM value may be unreasonably small DETAILS: lowestRecPPEM = 6
* :warning: **WARN** MS-FonVal: Ascender is different than OS/2.usWinAscent. Different line heights on Windows and Apple DETAILS: hhea.Ascender = 750, OS/2.usWinAscent = 1054
* :warning: **WARN** MS-FonVal: Descender is different than OS/2.usWinDescent. Different line heights on Windows and Apple DETAILS: hhea.Descender = -250, OS/2.usWinDescent = 364
* :warning: **WARN** MS-FonVal: The LineGap value is less than the recommended value DETAILS: LineGap = 0, recommended = 418
* :warning: **WARN** MS-FonVal: maxSizeOfInstructions computation not via either approved method DETAILS: glyf maxSizeOfInstructions=199, prep size=178, fpgm size=3590, whereas maxp maxSizeOfInstruction is 3590

</details>
<details>
<summary>:fire: <b>FAIL:</b> Check if OS/2 xAvgCharWidth is correct.</summary>

* [com.google.fonts/check/034](https://github.com/googlefonts/fontbakery/search?q=com.google.fonts/check/034)
* :fire: **FAIL** OS/2 xAvgCharWidth is 664 but it should be 675 which corresponds to the weighted average of the widths of the latin lowercase glyphs in the font

</details>
<details>
<summary>:warning: <b>WARN:</b> Checking OS/2 achVendID.</summary>

* [com.google.fonts/check/018](https://github.com/googlefonts/fontbakery/search?q=com.google.fonts/check/018)
* :warning: **WARN** OS/2 VendorID value 'NONE' is not a known registered id. You should set it to your own 4 character code, and register that code with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx [code: unknown]

</details>
<details>
<summary>:warning: <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/153](https://github.com/googlefonts/fontbakery/search?q=com.google.fonts/check/153)
* :warning: **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uniE000	Contours detected: 0	Expected: 1

</details>
<br>
</details>

### Summary

| :broken_heart: ERROR | :fire: FAIL | :warning: WARN | :zzz: SKIP | :information_source: INFO | :bread: PASS |
|:-----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 4 | 2 | 29 | 7 | 94 |
| 0% | 3% | 1% | 21% | 5% | 69% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**