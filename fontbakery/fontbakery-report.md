## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[19] VICWANTSchoolhand-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "VICWANTSchoolhand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, coptic, canadian-aboriginal, math, syriac, tifinagh, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, khmer, tai-tham, avestan, takri, thai, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, hatran, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, sogdian, sharada, tibetan, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, javanese, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, grantha
 * U+200D ZERO WIDTH JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, tai-tham, avestan, takri, thai, old-hungarian, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, tibetan, grantha, sharada, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, javanese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: khudawadi, yi, khmer, marchen, telugu, buginese, oriya, elbasan, syloti-nagri, meetei-mayek, psalter-pahlavi, gujarati, caucasian-albanian, cham, miao, kannada, tai-viet, siddham, devanagari, thai, nko, lepcha, malayalam, music, gunjala-gondi, old-permic, tibetan, osage, thaana, hanunoo, mende-kikakui, gurmukhi, duployan, bhaiksuki, tai-le, bassa-vah, phags-pa, buhid, hebrew, tagalog, javanese, tamil, pahawh-hmong, limbu, sinhala, coptic, zanabazar-square, mahajani, dogra, tagbanwa, bengali, sogdian, ahom, newa, manichaean, modi, khojki, tirhuta, hanifi-rohingya, takri, adlam, mandaic, syriac, tifinagh, balinese, symbols, sharada, kayah-li, kharoshthi, soyombo, chakma, sundanese, rejang, masaram-gondi, mongolian, batak, new-tai-lue, brahmi, math, wancho, kaithi, lao, myanmar, grantha
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- t.fina.alt

	- uni00A0.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1155 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 1083:
less

Width = 1156:
equal, lessequal, greaterequal

Width = 1086:
greater

Width = 1169:
plusminus

Width = 1090:
multiply

Width = 1159:
approxequal

Width = 1184:
notequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent (U+0025): X=1265.0,Y=1834.0 (should be at cap-height 1835?)

	* slash (U+002F): X=864.0,Y=1834.0 (should be at cap-height 1835?)

	* eight (U+0038): X=844.5,Y=1834.5 (should be at cap-height 1835?)

	* nine (U+0039): X=1286.0,Y=1833.5 (should be at cap-height 1835?)

	* B (U+0042): X=440.5,Y=1834.5 (should be at cap-height 1835?)

	* J (U+004A): X=163.5,Y=1.0 (should be at baseline 0?)

	* M (U+004D): X=855.0,Y=1833.0 (should be at cap-height 1835?)

	* N (U+004E): X=1401.0,Y=1834.0 (should be at cap-height 1835?)

	* W (U+0057): X=2291.0,Y=1835.5 (should be at cap-height 1835?)

	* X (U+0058): X=128.0,Y=2.0 (should be at baseline 0?)

	* Y (U+0059): X=446.5,Y=1835.5 (should be at cap-height 1835?)

	* d (U+0064): X=1009.0,Y=1833.0 (should be at cap-height 1835?)

	* h (U+0068): X=433.0,Y=1833.0 (should be at cap-height 1835?)

	* k (U+006B): X=433.5,Y=1833.0 (should be at cap-height 1835?)

	* k (U+006B): X=997.0,Y=994.0 (should be at x-height 995?)

	* l (U+006C): X=433.0,Y=1833.0 (should be at cap-height 1835?)

	* r (U+0072): X=796.0,Y=996.0 (should be at x-height 995?)

	* s (U+0073): X=296.5,Y=-0.5 (should be at baseline 0?)

	* v (U+0076): X=385.0,Y=-1.0 (should be at baseline 0?)

	* v (U+0076): X=385.0,Y=-1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=854.0,Y=1833.0 (should be at cap-height 1835?)

	* AE (U+00C6): X=884.5,Y=1836.0 (should be at cap-height 1835?)

	* Ccedilla (U+00C7): X=674.0,Y=-1.0 (should be at baseline 0?)

	* Ntilde (U+00D1): X=1401.0,Y=1834.0 (should be at cap-height 1835?)

	* Yacute (U+00DD): X=446.5,Y=1835.5 (should be at cap-height 1835?)

	* germandbls (U+00DF): X=759.5,Y=1834.0 (should be at cap-height 1835?)

	* ccedilla (U+00E7): X=281.0,Y=-1.0 (should be at baseline 0?)

	* oslash (U+00F8): X=357.0,Y=2.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=1116.5,Y=2574.0 (should be at ascender 2576?)

	* Ccaron (U+010C): X=1411.5,Y=2577.0 (should be at ascender 2576?)

	* Dcaron (U+010E): X=1024.5,Y=2574.0 (should be at ascender 2576?)

	* Dcaron (U+010E): X=1319.5,Y=2577.0 (should be at ascender 2576?)

	* dcaron (U+010F): X=1009.0,Y=1833.0 (should be at cap-height 1835?)

	* dcroat (U+0111): X=1009.0,Y=1833.0 (should be at cap-height 1835?)

	* Ecaron (U+011A): X=1019.5,Y=2574.0 (should be at ascender 2576?)

	* Ecaron (U+011A): X=1314.5,Y=2577.0 (should be at ascender 2576?)

	* hbar (U+0127): X=433.0,Y=1833.0 (should be at cap-height 1835?)

	* IJ (U+0132): X=1219.5,Y=1.0 (should be at baseline 0?)

	* uni0137 (U+0137): X=433.5,Y=1833.0 (should be at cap-height 1835?)

	* lacute (U+013A): X=433.0,Y=1833.0 (should be at cap-height 1835?)

	* uni013C (U+013C): X=433.0,Y=1833.0 (should be at cap-height 1835?)

	* lcaron (U+013E): X=433.0,Y=1833.0 (should be at cap-height 1835?)

	* Nacute (U+0143): X=1401.0,Y=1834.0 (should be at cap-height 1835?)

	* uni0145 (U+0145): X=1401.0,Y=1834.0 (should be at cap-height 1835?)

	* Ncaron (U+0147): X=1401.0,Y=1834.0 (should be at cap-height 1835?)

	* Ncaron (U+0147): X=1005.5,Y=2574.0 (should be at ascender 2576?)

	* Ncaron (U+0147): X=1300.5,Y=2577.0 (should be at ascender 2576?)

	* Eng (U+014A): X=245.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=449.0,Y=1834.0 (should be at cap-height 1835?)

	* Eng (U+014A): X=245.0,Y=-1.0 (should be at baseline 0?)

	* Rcaron (U+0158): X=927.5,Y=2574.0 (should be at ascender 2576?)

	* Rcaron (U+0158): X=1222.5,Y=2577.0 (should be at ascender 2576?)

	* sacute (U+015B): X=296.5,Y=-0.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=424.0,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=296.5,Y=-0.5 (should be at baseline 0?)

	* Scaron (U+0160): X=877.5,Y=2574.0 (should be at ascender 2576?)

	* Scaron (U+0160): X=1172.5,Y=2577.0 (should be at ascender 2576?)

	* scaron (U+0161): X=296.5,Y=-0.5 (should be at baseline 0?)

	* Uogonek (U+0172): X=985.5,Y=-1.5 (should be at baseline 0?)

	* uogonek (U+0173): X=616.5,Y=1.5 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=2291.0,Y=1835.5 (should be at cap-height 1835?)

	* Ycircumflex (U+0176): X=446.5,Y=1835.5 (should be at cap-height 1835?)

	* Ydieresis (U+0178): X=446.5,Y=1835.5 (should be at cap-height 1835?)

	* Zcaron (U+017D): X=813.5,Y=2574.0 (should be at ascender 2576?)

	* Zcaron (U+017D): X=1108.5,Y=2577.0 (should be at ascender 2576?)

	* uni01CD (U+01CD): X=965.5,Y=2574.0 (should be at ascender 2576?)

	* uni01CD (U+01CD): X=1260.5,Y=2577.0 (should be at ascender 2576?)

	* uni01D1 (U+01D1): X=1038.5,Y=2574.0 (should be at ascender 2576?)

	* uni01D1 (U+01D1): X=1333.5,Y=2577.0 (should be at ascender 2576?)

	* Gcaron (U+01E6): X=1057.5,Y=2574.0 (should be at ascender 2576?)

	* Gcaron (U+01E6): X=1352.5,Y=2577.0 (should be at ascender 2576?)

	* uni0219 (U+0219): X=296.5,Y=-0.5 (should be at baseline 0?)

	* uni1E3E (U+1E3E): X=855.0,Y=1833.0 (should be at cap-height 1835?)

	* Wgrave (U+1E80): X=2291.0,Y=1835.5 (should be at cap-height 1835?)

	* Wacute (U+1E82): X=2291.0,Y=1835.5 (should be at cap-height 1835?)

	* Wdieresis (U+1E84): X=2291.0,Y=1835.5 (should be at cap-height 1835?)

	* uni1E9E (U+1E9E): X=1698.5,Y=1837.0 (should be at cap-height 1835?)

	* Ygrave (U+1EF2): X=446.5,Y=1835.5 (should be at cap-height 1835?)

	* uni1EF8 (U+1EF8): X=446.5,Y=1835.5 (should be at cap-height 1835?)

	* quoteleft (U+2018): X=511.0,Y=1836.5 (should be at cap-height 1835?)

	* quotedblleft (U+201C): X=508.0,Y=1836.5 (should be at cap-height 1835?)

	* quotedblleft (U+201C): X=902.0,Y=1836.5 (should be at cap-height 1835?)

	* uni2116 (U+2116): X=1401.0,Y=1834.0 (should be at cap-height 1835?)

	* estimated (U+212E): X=1757.5,Y=1833.5 (should be at cap-height 1835?)

	* fl (U+FB02): X=1222.0,Y=1833.0 (should be at cap-height 1835?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* six (U+0036) contains a short segment B<<413.0,1190.0>-<408.0,1182.0>-<400.5,1171.5>>

	* at (U+0040) contains a short segment B<<1283.0,512.0>-<1278.0,491.0>-<1273.5,462.0>>

	* at (U+0040) contains a short segment B<<1273.5,462.0>-<1269.0,433.0>-<1273.5,411.0>>

	* at (U+0040) contains a short segment B<<1273.5,411.0>-<1278.0,389.0>-<1300.0,389.0>>

	* M (U+004D) contains a short segment B<<1245.0,89.0>-<1232.0,64.0>-<1201.5,32.0>>

	* Q (U+0051) contains a short segment B<<802.0,257.0>-<810.0,257.0>-<818.0,257.5>>

	* Q (U+0051) contains a short segment B<<818.0,257.5>-<826.0,258.0>-<834.0,259.0>>

	* W (U+0057) contains a short segment B<<1124.0,1769.0>-<1137.0,1796.0>-<1164.0,1826.5>>

	* W (U+0057) contains a short segment B<<2291.0,1835.5>-<2325.0,1814.0>-<2337.0,1776.5>>

	* Z (U+005A) contains a short segment B<<1391.0,1745.0>-<1391.0,1723.0>-<1383.0,1699.0>>

	* k (U+006B) contains a short segment B<<594.5,522.0>-<608.0,541.0>-<624.0,551.0>>

	* k (U+006B) contains a short segment B<<824.0,748.0>-<824.0,776.0>-<800.0,776.0>>

	* p (U+0070) contains a short segment L<<1047.0,455.0>--<1056.0,460.0>>

	* q (U+0071) contains a short segment L<<869.0,-397.0>--<878.0,-392.0>>

	* v (U+0076) contains a short segment B<<1052.0,1001.0>-<1058.0,1001.0>-<1073.0,998.5>>

	* v (U+0076) contains a short segment L<<1095.0,705.0>--<1088.0,688.0>>

	* w (U+0077) contains a short segment B<<1742.0,1001.0>-<1747.0,1001.0>-<1762.0,998.5>>

	* w (U+0077) contains a short segment L<<1783.0,705.0>--<1776.0,688.0>>

	* sterling (U+00A3) contains a short segment B<<612.0,1585.0>-<593.0,1578.0>-<586.0,1563.0>>

	* sterling (U+00A3) contains a short segment B<<586.0,1563.0>-<579.0,1548.0>-<575.0,1530.0>>

	* sterling (U+00A3) contains a short segment B<<34.0,115.5>-<43.0,141.0>-<56.0,156.0>>

	* yen (U+00A5) contains a short segment B<<239.0,1674.0>-<230.0,1698.0>-<226.0,1714.0>>

	* yen (U+00A5) contains a short segment B<<226.0,1714.0>-<222.0,1730.0>-<222.0,1752.0>>

	* oslash (U+00F8) contains a short segment L<<568.0,765.0>--<567.0,765.0>>

	* Dcroat (U+0110) contains a short segment L<<232.0,852.0>--<222.0,852.0>>

	* uni0137 (U+0137) contains a short segment B<<594.5,522.0>-<608.0,541.0>-<624.0,551.0>>

	* uni0137 (U+0137) contains a short segment B<<824.0,748.0>-<824.0,776.0>-<800.0,776.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1124.0,1769.0>-<1137.0,1796.0>-<1164.0,1826.5>>

	* Wcircumflex (U+0174) contains a short segment B<<2291.0,1835.5>-<2325.0,1814.0>-<2337.0,1776.5>>

	* wcircumflex (U+0175) contains a short segment B<<1742.0,1001.0>-<1747.0,1001.0>-<1762.0,998.5>>

	* wcircumflex (U+0175) contains a short segment L<<1783.0,705.0>--<1776.0,688.0>>

	* Zacute (U+0179) contains a short segment B<<1391.0,1745.0>-<1391.0,1723.0>-<1383.0,1699.0>>

	* Zdotaccent (U+017B) contains a short segment B<<1391.0,1745.0>-<1391.0,1723.0>-<1383.0,1699.0>>

	* Zcaron (U+017D) contains a short segment B<<1391.0,1745.0>-<1391.0,1723.0>-<1383.0,1699.0>>

	* uni1E3E (U+1E3E) contains a short segment B<<1245.0,89.0>-<1232.0,64.0>-<1201.5,32.0>>

	* Wgrave (U+1E80) contains a short segment B<<1124.0,1769.0>-<1137.0,1796.0>-<1164.0,1826.5>>

	* Wgrave (U+1E80) contains a short segment B<<2291.0,1835.5>-<2325.0,1814.0>-<2337.0,1776.5>>

	* wgrave (U+1E81) contains a short segment B<<1742.0,1001.0>-<1747.0,1001.0>-<1762.0,998.5>>

	* wgrave (U+1E81) contains a short segment L<<1783.0,705.0>--<1776.0,688.0>>

	* Wacute (U+1E82) contains a short segment B<<1124.0,1769.0>-<1137.0,1796.0>-<1164.0,1826.5>>

	* Wacute (U+1E82) contains a short segment B<<2291.0,1835.5>-<2325.0,1814.0>-<2337.0,1776.5>>

	* wacute (U+1E83) contains a short segment B<<1742.0,1001.0>-<1747.0,1001.0>-<1762.0,998.5>>

	* wacute (U+1E83) contains a short segment L<<1783.0,705.0>--<1776.0,688.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1124.0,1769.0>-<1137.0,1796.0>-<1164.0,1826.5>>

	* Wdieresis (U+1E84) contains a short segment B<<2291.0,1835.5>-<2325.0,1814.0>-<2337.0,1776.5>>

	* wdieresis (U+1E85) contains a short segment B<<1742.0,1001.0>-<1747.0,1001.0>-<1762.0,998.5>>

	* wdieresis (U+1E85) contains a short segment L<<1783.0,705.0>--<1776.0,688.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<696.0,0.0>-<676.0,1.0>-<643.5,11.0>>

	* daggerdbl (U+2021) contains a short segment L<<461.0,781.0>--<432.0,781.0>>

	* Euro (U+20AC) contains a short segment B<<345.0,789.0>-<347.0,809.0>-<350.0,830.0>>

	* Euro (U+20AC) contains a short segment B<<350.0,830.0>-<353.0,851.0>-<356.0,871.0>>

	* Euro (U+20AC) contains a short segment B<<356.0,871.0>-<358.0,882.0>-<360.5,894.0>>

	* Euro (U+20AC) contains a short segment B<<360.5,894.0>-<363.0,906.0>-<364.0,917.0>>

	* Euro (U+20AC) contains a short segment B<<652.0,917.0>-<649.0,905.0>-<647.0,893.0>>

	* Euro (U+20AC) contains a short segment B<<647.0,893.0>-<645.0,881.0>-<643.0,869.0>>

	* Euro (U+20AC) contains a short segment B<<643.0,869.0>-<639.0,849.0>-<636.5,829.0>>

	* Euro (U+20AC) contains a short segment B<<636.5,829.0>-<634.0,809.0>-<632.0,789.0>>

	* estimated (U+212E) contains a short segment B<<578.0,948.0>-<559.0,948.0>-<547.5,940.5>>

	* estimated (U+212E) contains a short segment B<<547.5,940.5>-<536.0,933.0>-<536.0,896.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<927.0,1492.0>--<844.0,1282.0>> -> L<<844.0,1282.0>--<738.0,1074.0>>

	* oslash (U+00F8): L<<377.0,381.0>--<444.0,503.0>> -> L<<444.0,503.0>--<568.0,765.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* six (U+0036): B<<372.0,1132.0>-<351.0,1103.0>-<305.0,1039.0>>/B<<305.0,1039.0>-<393.0,1116.0>-<465.0,1153.5>> = 13.107383433687474 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* arrowleft (U+2190): L<<1535.0,754.0>--<640.0,755.0>>

	* arrowleft (U+2190): L<<674.0,993.0>--<1546.0,992.0>>

	* arrowright (U+2192): L<<1131.0,797.0>--<259.0,798.0>>

	* arrowright (U+2192): L<<270.0,1036.0>--<1165.0,1035.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] VICWANTSchoolhand-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "VICWANTSchoolhand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, coptic, canadian-aboriginal, math, syriac, tifinagh, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, khmer, tai-tham, avestan, takri, thai, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, hatran, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, sogdian, sharada, tibetan, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, javanese, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, grantha
 * U+200D ZERO WIDTH JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, tai-tham, avestan, takri, thai, old-hungarian, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, tibetan, grantha, sharada, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, javanese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: khudawadi, yi, khmer, marchen, telugu, buginese, oriya, elbasan, syloti-nagri, meetei-mayek, psalter-pahlavi, gujarati, caucasian-albanian, cham, miao, kannada, tai-viet, siddham, devanagari, thai, nko, lepcha, malayalam, music, gunjala-gondi, old-permic, tibetan, osage, thaana, hanunoo, mende-kikakui, gurmukhi, duployan, bhaiksuki, tai-le, bassa-vah, phags-pa, buhid, hebrew, tagalog, javanese, tamil, pahawh-hmong, limbu, sinhala, coptic, zanabazar-square, mahajani, dogra, tagbanwa, bengali, sogdian, ahom, newa, manichaean, modi, khojki, tirhuta, hanifi-rohingya, takri, adlam, mandaic, syriac, tifinagh, balinese, symbols, sharada, kayah-li, kharoshthi, soyombo, chakma, sundanese, rejang, masaram-gondi, mongolian, batak, new-tai-lue, brahmi, math, wancho, kaithi, lao, myanmar, grantha
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'VICWANTSchoolhand Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- t.fina.alt

	- uni00A0.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1081 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 1018:
less

Width = 1082:
equal

Width = 1020:
greater

Width = 1101:
plusminus

Width = 1048:
multiply

Width = 1102:
approxequal

Width = 1106:
notequal

Width = 1094:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=393.0,Y=-2.0 (should be at baseline 0?)

	* percent (U+0025): X=1024.0,Y=1839.0 (should be at cap-height 1841?)

	* slash (U+002F): X=706.5,Y=1839.0 (should be at cap-height 1841?)

	* four (U+0034): X=780.0,Y=1841.5 (should be at cap-height 1841?)

	* eight (U+0038): X=835.0,Y=1839.0 (should be at cap-height 1841?)

	* nine (U+0039): X=1250.5,Y=1840.0 (should be at cap-height 1841?)

	* B (U+0042): X=430.5,Y=1839.5 (should be at cap-height 1841?)

	* J (U+004A): X=65.5,Y=-1.5 (should be at baseline 0?)

	* M (U+004D): X=873.5,Y=1839.5 (should be at cap-height 1841?)

	* T (U+0054): X=572.0,Y=-1.0 (should be at baseline 0?)

	* T (U+0054): X=572.0,Y=-1.0 (should be at baseline 0?)

	* V (U+0056): X=1207.0,Y=1841.5 (should be at cap-height 1841?)

	* X (U+0058): X=1319.0,Y=1839.0 (should be at cap-height 1841?)

	* X (U+0058): X=931.5,Y=1.5 (should be at baseline 0?)

	* Y (U+0059): X=384.5,Y=1843.0 (should be at cap-height 1841?)

	* b (U+0062): X=757.0,Y=996.0 (should be at x-height 995?)

	* d (U+0064): X=1004.5,Y=1842.0 (should be at cap-height 1841?)

	* f (U+0066): X=109.0,Y=997.0 (should be at x-height 995?)

	* f (U+0066): X=278.0,Y=997.0 (should be at x-height 995?)

	* f (U+0066): X=478.0,Y=997.0 (should be at x-height 995?)

	* f (U+0066): X=625.0,Y=997.0 (should be at x-height 995?)

	* l (U+006C): X=427.5,Y=1840.0 (should be at cap-height 1841?)

	* s (U+0073): X=617.5,Y=997.0 (should be at x-height 995?)

	* t (U+0074): X=182.0,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=182.0,Y=1.0 (should be at baseline 0?)

	* v (U+0076): X=333.0,Y=997.0 (should be at x-height 995?)

	* v (U+0076): X=1023.0,Y=997.0 (should be at x-height 995?)

	* v (U+0076): X=1046.5,Y=994.0 (should be at x-height 995?)

	* x (U+0078): X=96.5,Y=1.0 (should be at baseline 0?)

	* AE (U+00C6): X=882.5,Y=1840.0 (should be at cap-height 1841?)

	* Yacute (U+00DD): X=384.5,Y=1843.0 (should be at cap-height 1841?)

	* germandbls (U+00DF): X=1073.0,Y=1842.0 (should be at cap-height 1841?)

	* aring (U+00E5): X=890.0,Y=1839.0 (should be at cap-height 1841?)

	* ccedilla (U+00E7): X=263.0,Y=-2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=432.5,Y=1839.0 (should be at cap-height 1841?)

	* dcaron (U+010F): X=1004.5,Y=1842.0 (should be at cap-height 1841?)

	* dcroat (U+0111): X=1004.5,Y=1842.0 (should be at cap-height 1841?)

	* IJ (U+0132): X=990.5,Y=-1.5 (should be at baseline 0?)

	* lacute (U+013A): X=427.5,Y=1840.0 (should be at cap-height 1841?)

	* uni013C (U+013C): X=427.5,Y=1840.0 (should be at cap-height 1841?)

	* lcaron (U+013E): X=427.5,Y=1840.0 (should be at cap-height 1841?)

	* Eng (U+014A): X=1024.5,Y=-1.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=572.0,Y=-1.0 (should be at baseline 0?)

	* uni0162 (U+0162): X=572.0,Y=-1.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=182.0,Y=1.0 (should be at baseline 0?)

	* uni0163 (U+0163): X=182.0,Y=1.0 (should be at baseline 0?)

	* Tcaron (U+0164): X=572.0,Y=-1.0 (should be at baseline 0?)

	* Tcaron (U+0164): X=572.0,Y=-1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=182.0,Y=1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=182.0,Y=1.0 (should be at baseline 0?)

	* Ycircumflex (U+0176): X=384.5,Y=1843.0 (should be at cap-height 1841?)

	* Ydieresis (U+0178): X=384.5,Y=1843.0 (should be at cap-height 1841?)

	* uni021A (U+021A): X=572.0,Y=-1.0 (should be at baseline 0?)

	* uni021A (U+021A): X=572.0,Y=-1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=182.0,Y=1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=182.0,Y=1.0 (should be at baseline 0?)

	* uni1E3E (U+1E3E): X=873.5,Y=1839.5 (should be at cap-height 1841?)

	* uni1E9E (U+1E9E): X=826.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=826.0,Y=-2.0 (should be at baseline 0?)

	* Ygrave (U+1EF2): X=384.5,Y=1843.0 (should be at cap-height 1841?)

	* uni1EF8 (U+1EF8): X=384.5,Y=1843.0 (should be at cap-height 1841?)

	* quoteleft (U+2018): X=447.0,Y=1843.0 (should be at cap-height 1841?)

	* quotedblleft (U+201C): X=446.0,Y=1843.0 (should be at cap-height 1841?)

	* quotedblleft (U+201C): X=758.0,Y=1843.0 (should be at cap-height 1841?)

	* trademark (U+2122): X=283.5,Y=1840.5 (should be at cap-height 1841?)

	* trademark (U+2122): X=921.0,Y=1840.5 (should be at cap-height 1841?)

	* estimated (U+212E): X=939.0,Y=1840.0 (should be at cap-height 1841?)

	* fl (U+FB02): X=1115.5,Y=1840.0 (should be at cap-height 1841?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* AE (U+00C6): L<<912.0,1604.0>--<819.0,1377.0>> -> L<<819.0,1377.0>--<662.0,1063.0>>

	* AE (U+00C6): L<<937.0,1063.0>--<912.0,1367.0>> -> L<<912.0,1367.0>--<912.0,1604.0>>

	* Aacute (U+00C1): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Abreve (U+0102): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Acircumflex (U+00C2): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Adieresis (U+00C4): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Agrave (U+00C0): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Amacron (U+0100): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Aogonek (U+0104): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Aring (U+00C5): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* Atilde (U+00C3): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* oslash (U+00F8): L<<312.0,263.0>--<440.0,512.0>> -> L<<440.0,512.0>--<593.0,833.0>>

	* oslash (U+00F8): L<<701.0,748.0>--<545.0,460.0>> -> L<<545.0,460.0>--<411.0,169.0>>

	* uni01CD (U+01CD): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>>

	* uni01DE (U+01DE): L<<923.0,1618.0>--<821.0,1376.0>> -> L<<821.0,1376.0>--<644.0,1030.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* U (U+0055): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Uacute (U+00DA): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Ubreve (U+016C): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Ucircumflex (U+00DB): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Udieresis (U+00DC): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Ugrave (U+00D9): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Uhungarumlaut (U+0170): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Umacron (U+016A): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Uogonek (U+0172): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Uring (U+016E): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964

	* Utilde (U+0168): L<<1068.0,100.0>--<1186.0,770.0>>/B<<1186.0,770.0>-<1069.0,509.0>-<933.5,334.0>> = 14.157077069503964 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* arrowleft (U+2190): L<<1481.0,768.0>--<459.0,769.0>>

	* arrowleft (U+2190): L<<488.0,948.0>--<1501.0,947.0>>

	* arrowright (U+2192): L<<1199.0,809.0>--<186.0,810.0>>

	* uni1E9E (U+1E9E): L<<625.0,184.0>--<826.0,183.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[17] VICWANTSchoolhand-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "VICWANTSchoolhand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, coptic, canadian-aboriginal, math, syriac, tifinagh, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, khmer, tai-tham, avestan, takri, thai, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, hatran, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, sogdian, sharada, tibetan, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, javanese, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, grantha
 * U+200D ZERO WIDTH JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, tai-tham, avestan, takri, thai, old-hungarian, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, tibetan, grantha, sharada, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, javanese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: khudawadi, yi, khmer, marchen, telugu, buginese, oriya, elbasan, syloti-nagri, meetei-mayek, psalter-pahlavi, gujarati, caucasian-albanian, cham, miao, kannada, tai-viet, siddham, devanagari, thai, nko, lepcha, malayalam, music, gunjala-gondi, old-permic, tibetan, osage, thaana, hanunoo, mende-kikakui, gurmukhi, duployan, bhaiksuki, tai-le, bassa-vah, phags-pa, buhid, hebrew, tagalog, javanese, tamil, pahawh-hmong, limbu, sinhala, coptic, zanabazar-square, mahajani, dogra, tagbanwa, bengali, sogdian, ahom, newa, manichaean, modi, khojki, tirhuta, hanifi-rohingya, takri, adlam, mandaic, syriac, tifinagh, balinese, symbols, sharada, kayah-li, kharoshthi, soyombo, chakma, sundanese, rejang, masaram-gondi, mongolian, batak, new-tai-lue, brahmi, math, wancho, kaithi, lao, myanmar, grantha
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- t.fina.alt

	- uni00A0.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1017 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 961:
less

Width = 962:
greater

Width = 1042:
plusminus

Width = 1011:
multiply

Width = 1052:
approxequal

Width = 1037:
notequal

Width = 1039:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* A (U+0041): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* AE (U+00C6): L<<899.0,1702.0>--<798.0,1461.0>> -> L<<798.0,1461.0>--<596.0,1054.0>>

	* AE (U+00C6): L<<938.0,1054.0>--<907.0,1444.0>> -> L<<907.0,1444.0>--<899.0,1702.0>>

	* Aacute (U+00C1): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Aacute (U+00C1): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Abreve (U+0102): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Abreve (U+0102): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Acircumflex (U+00C2): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Acircumflex (U+00C2): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Adieresis (U+00C4): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Adieresis (U+00C4): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Agrave (U+00C0): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Agrave (U+00C0): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Amacron (U+0100): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Amacron (U+0100): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Aogonek (U+0104): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Aogonek (U+0104): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Aring (U+00C5): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Aring (U+00C5): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* Atilde (U+00C3): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* Atilde (U+00C3): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* oslash (U+00F8): L<<267.0,174.0>--<437.0,519.0>> -> L<<437.0,519.0>--<612.0,888.0>>

	* oslash (U+00F8): L<<707.0,818.0>--<533.0,465.0>> -> L<<533.0,465.0>--<363.0,107.0>>

	* uni01CD (U+01CD): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* uni01CD (U+01CD): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>>

	* uni01DE (U+01DE): L<<920.0,1726.0>--<800.0,1458.0>> -> L<<800.0,1458.0>--<594.0,1055.0>>

	* uni01DE (U+01DE): L<<951.0,1055.0>--<920.0,1439.0>> -> L<<920.0,1439.0>--<920.0,1726.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* U (U+0055): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Uacute (U+00DA): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Ubreve (U+016C): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Ucircumflex (U+00DB): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Udieresis (U+00DC): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Ugrave (U+00D9): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Uhungarumlaut (U+0170): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Umacron (U+016A): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Uogonek (U+0172): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Uring (U+016E): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274

	* Utilde (U+0168): L<<1071.0,65.0>--<1235.0,993.0>>/B<<1235.0,993.0>-<1101.0,651.0>-<947.0,426.5>> = 11.373817184570274 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* arrowleft (U+2190): L<<326.0,909.0>--<1462.0,908.0>>

	* arrowright (U+2192): L<<1259.0,820.0>--<123.0,821.0>>

	* uni1E9E (U+1E9E): L<<755.0,-1.0>--<565.0,0.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] VICWANTSchoolhand-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "VICWANTSchoolhand" contains an abbreviation. [code: abbreviation]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, coptic, canadian-aboriginal, math, syriac, tifinagh, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+2000 EN QUAD: not included in any glyphset definition
 * U+2001 EM QUAD: not included in any glyphset definition
 * U+2003 EM SPACE: try adding nushu
 * U+2004 THREE-PER-EM SPACE: not included in any glyphset definition
 * U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition
 * U+2006 SIX-PER-EM SPACE: not included in any glyphset definition
 * U+2007 FIGURE SPACE: not included in any glyphset definition
 * U+2008 PUNCTUATION SPACE: not included in any glyphset definition
 * U+200A HAIR SPACE: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, khmer, tai-tham, avestan, takri, thai, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, hatran, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, sogdian, sharada, tibetan, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, javanese, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, grantha
 * U+200D ZERO WIDTH JOINER: try adding one of: tamil, pahawh-hmong, siddham, hanifi-rohingya, khudawadi, yi, devanagari, tai-tham, avestan, takri, thai, old-hungarian, telugu, nko, limbu, lepcha, malayalam, sinhala, buginese, warang-citi, mandaic, mahajani, dogra, syriac, oriya, tirhuta, gunjala-gondi, syloti-nagri, meetei-mayek, tagbanwa, tifinagh, bengali, balinese, psalter-pahlavi, tibetan, grantha, sharada, tagalog, kayah-li, kharoshthi, chakma, gujarati, sundanese, thaana, saurashtra, hanunoo, gurmukhi, duployan, newa, rejang, tai-le, manichaean, cham, mongolian, batak, new-tai-lue, brahmi, buhid, phags-pa, kannada, kaithi, modi, tai-viet, khojki, myanmar, javanese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi
 * U+205F MEDIUM MATHEMATICAL SPACE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+221E INFINITY: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: khudawadi, yi, khmer, marchen, telugu, buginese, oriya, elbasan, syloti-nagri, meetei-mayek, psalter-pahlavi, gujarati, caucasian-albanian, cham, miao, kannada, tai-viet, siddham, devanagari, thai, nko, lepcha, malayalam, music, gunjala-gondi, old-permic, tibetan, osage, thaana, hanunoo, mende-kikakui, gurmukhi, duployan, bhaiksuki, tai-le, bassa-vah, phags-pa, buhid, hebrew, tagalog, javanese, tamil, pahawh-hmong, limbu, sinhala, coptic, zanabazar-square, mahajani, dogra, tagbanwa, bengali, sogdian, ahom, newa, manichaean, modi, khojki, tirhuta, hanifi-rohingya, takri, adlam, mandaic, syriac, tifinagh, balinese, symbols, sharada, kayah-li, kharoshthi, soyombo, chakma, sundanese, rejang, masaram-gondi, mongolian, batak, new-tai-lue, brahmi, math, wancho, kaithi, lao, myanmar, grantha
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'VICWANTSchoolhand SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.7395x (3479) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- t.fina.alt

	- uni00A0.001
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 1	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: oe	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 1	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 1127 among a set of 3 math glyphs.
The following math glyphs have a different width, though:

Width = 1059:
less

Width = 1128:
equal

Width = 1061:
greater

Width = 1144:
plusminus

Width = 1074:
multiply

Width = 1138:
approxequal

Width = 1155:
notequal

Width = 1133:
lessequal, greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<1243.0,516.0>-<1234.0,483.0>-<1229.5,448.0>>

	* at (U+0040) contains a short segment B<<1229.5,448.0>-<1225.0,413.0>-<1231.5,388.5>>

	* at (U+0040) contains a short segment B<<1231.5,388.5>-<1238.0,364.0>-<1261.0,364.0>>

	* M (U+004D) contains a short segment B<<73.0,-1.0>-<35.0,-1.0>-<4.0,21.5>>

	* M (U+004D) contains a short segment B<<4.0,21.5>-<-27.0,44.0>-<-37.0,81.5>>

	* M (U+004D) contains a short segment B<<816.0,1771.0>-<837.0,1813.0>-<861.5,1835.5>>

	* M (U+004D) contains a short segment B<<1229.0,83.0>-<1217.0,60.0>-<1189.0,29.5>>

	* W (U+0057) contains a short segment B<<1136.0,1775.0>-<1148.0,1800.0>-<1173.5,1829.0>>

	* W (U+0057) contains a short segment B<<517.5,24.0>-<485.0,-1.0>-<446.0,-1.0>>

	* Y (U+0059) contains a short segment B<<227.5,1731.0>-<224.0,1745.0>-<224.0,1765.0>>

	* Z (U+005A) contains a short segment B<<1374.0,1760.0>-<1374.0,1740.0>-<1366.5,1717.5>>

	* k (U+006B) contains a short segment B<<580.5,517.5>-<593.0,536.0>-<612.0,547.0>>

	* m (U+006D) contains a short segment B<<233.0,892.0>-<236.0,910.0>-<250.0,935.5>>

	* p (U+0070) contains a short segment L<<1010.0,404.0>--<1042.0,429.0>>

	* v (U+0076) contains a short segment B<<1041.0,1000.0>-<1047.0,1000.0>-<1063.0,997.0>>

	* v (U+0076) contains a short segment L<<1080.0,738.0>--<1071.0,717.0>>

	* w (U+0077) contains a short segment B<<1734.0,1001.0>-<1739.0,1001.0>-<1756.0,998.0>>

	* w (U+0077) contains a short segment L<<1771.0,739.0>--<1762.0,719.0>>

	* sterling (U+00A3) contains a short segment B<<610.0,1607.0>-<586.0,1597.0>-<576.5,1578.5>>

	* sterling (U+00A3) contains a short segment B<<576.5,1578.5>-<567.0,1560.0>-<564.0,1537.0>>

	* yen (U+00A5) contains a short segment B<<291.0,1691.0>-<283.0,1714.0>-<279.5,1727.5>>

	* yen (U+00A5) contains a short segment B<<279.5,1727.5>-<276.0,1741.0>-<276.0,1762.0>>

	* Yacute (U+00DD) contains a short segment B<<227.5,1731.0>-<224.0,1745.0>-<224.0,1765.0>>

	* Dcroat (U+0110) contains a short segment L<<236.0,872.0>--<209.0,872.0>>

	* uni0137 (U+0137) contains a short segment B<<580.5,517.5>-<593.0,536.0>-<612.0,547.0>>

	* Lslash (U+0141) contains a short segment L<<187.0,473.0>--<163.0,461.0>>

	* lslash (U+0142) contains a short segment L<<506.0,1003.0>--<526.0,1010.0>>

	* Wcircumflex (U+0174) contains a short segment B<<1136.0,1775.0>-<1148.0,1800.0>-<1173.5,1829.0>>

	* Wcircumflex (U+0174) contains a short segment B<<517.5,24.0>-<485.0,-1.0>-<446.0,-1.0>>

	* wcircumflex (U+0175) contains a short segment B<<1734.0,1001.0>-<1739.0,1001.0>-<1756.0,998.0>>

	* wcircumflex (U+0175) contains a short segment L<<1771.0,739.0>--<1762.0,719.0>>

	* Ycircumflex (U+0176) contains a short segment B<<227.5,1731.0>-<224.0,1745.0>-<224.0,1765.0>>

	* Ydieresis (U+0178) contains a short segment B<<227.5,1731.0>-<224.0,1745.0>-<224.0,1765.0>>

	* Zacute (U+0179) contains a short segment B<<1374.0,1760.0>-<1374.0,1740.0>-<1366.5,1717.5>>

	* Zdotaccent (U+017B) contains a short segment B<<1374.0,1760.0>-<1374.0,1740.0>-<1366.5,1717.5>>

	* Zcaron (U+017D) contains a short segment B<<1374.0,1760.0>-<1374.0,1740.0>-<1366.5,1717.5>>

	* uni1E3E (U+1E3E) contains a short segment B<<73.0,-1.0>-<35.0,-1.0>-<4.0,21.5>>

	* uni1E3E (U+1E3E) contains a short segment B<<4.0,21.5>-<-27.0,44.0>-<-37.0,81.5>>

	* uni1E3E (U+1E3E) contains a short segment B<<816.0,1771.0>-<837.0,1813.0>-<861.5,1835.5>>

	* uni1E3E (U+1E3E) contains a short segment B<<1229.0,83.0>-<1217.0,60.0>-<1189.0,29.5>>

	* uni1E3F (U+1E3F) contains a short segment B<<233.0,892.0>-<236.0,910.0>-<250.0,935.5>>

	* Wgrave (U+1E80) contains a short segment B<<1136.0,1775.0>-<1148.0,1800.0>-<1173.5,1829.0>>

	* Wgrave (U+1E80) contains a short segment B<<517.5,24.0>-<485.0,-1.0>-<446.0,-1.0>>

	* wgrave (U+1E81) contains a short segment B<<1734.0,1001.0>-<1739.0,1001.0>-<1756.0,998.0>>

	* wgrave (U+1E81) contains a short segment L<<1771.0,739.0>--<1762.0,719.0>>

	* Wacute (U+1E82) contains a short segment B<<1136.0,1775.0>-<1148.0,1800.0>-<1173.5,1829.0>>

	* Wacute (U+1E82) contains a short segment B<<517.5,24.0>-<485.0,-1.0>-<446.0,-1.0>>

	* wacute (U+1E83) contains a short segment B<<1734.0,1001.0>-<1739.0,1001.0>-<1756.0,998.0>>

	* wacute (U+1E83) contains a short segment L<<1771.0,739.0>--<1762.0,719.0>>

	* Wdieresis (U+1E84) contains a short segment B<<1136.0,1775.0>-<1148.0,1800.0>-<1173.5,1829.0>>

	* Wdieresis (U+1E84) contains a short segment B<<517.5,24.0>-<485.0,-1.0>-<446.0,-1.0>>

	* wdieresis (U+1E85) contains a short segment B<<1734.0,1001.0>-<1739.0,1001.0>-<1756.0,998.0>>

	* wdieresis (U+1E85) contains a short segment L<<1771.0,739.0>--<1762.0,719.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<670.0,0.0>-<651.0,0.0>-<622.5,9.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<622.5,9.5>-<594.0,19.0>-<572.0,42.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<1679.5,1839.5>-<1709.0,1822.0>-<1724.0,1793.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<1724.0,1793.0>-<1738.0,1765.0>-<1736.0,1730.0>>

	* Ygrave (U+1EF2) contains a short segment B<<227.5,1731.0>-<224.0,1745.0>-<224.0,1765.0>>

	* uni1EF8 (U+1EF8) contains a short segment B<<227.5,1731.0>-<224.0,1745.0>-<224.0,1765.0>>

	* Euro (U+20AC) contains a short segment B<<367.0,771.0>-<369.0,796.0>-<372.0,820.5>>

	* Euro (U+20AC) contains a short segment B<<372.0,820.5>-<375.0,845.0>-<379.0,871.0>>

	* Euro (U+20AC) contains a short segment B<<379.0,871.0>-<382.0,887.0>-<385.0,902.0>>

	* Euro (U+20AC) contains a short segment B<<385.0,902.0>-<388.0,917.0>-<391.0,934.0>>

	* Euro (U+20AC) contains a short segment B<<644.0,934.0>-<640.0,917.0>-<637.5,901.5>>

	* Euro (U+20AC) contains a short segment B<<637.5,901.5>-<635.0,886.0>-<632.0,869.0>>

	* estimated (U+212E) contains a short segment B<<578.0,948.0>-<559.0,948.0>-<547.5,940.5>>

	* estimated (U+212E) contains a short segment B<<547.5,940.5>-<536.0,933.0>-<536.0,896.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* AE (U+00C6): L<<921.0,1534.0>--<835.0,1318.0>> -> L<<835.0,1318.0>--<710.0,1070.0>>

	* Aacute (U+00C1): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Abreve (U+0102): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Acircumflex (U+00C2): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Adieresis (U+00C4): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Agrave (U+00C0): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Amacron (U+0100): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Aogonek (U+0104): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Aring (U+00C5): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* Atilde (U+00C3): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* oslash (U+00F8): L<<351.0,334.0>--<443.0,506.0>> -> L<<443.0,506.0>--<578.0,791.0>>

	* oslash (U+00F8): L<<691.0,695.0>--<554.0,457.0>> -> L<<554.0,457.0>--<444.0,213.0>>

	* uni01CD (U+01CD): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>>

	* uni01DE (U+01DE): L<<925.0,1540.0>--<835.0,1317.0>> -> L<<835.0,1317.0>--<680.0,1012.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* arrowleft (U+2190): L<<1515.0,759.0>--<572.0,760.0>>

	* arrowleft (U+2190): L<<604.0,976.0>--<1529.0,975.0>>

	* arrowright (U+2192): L<<1157.0,802.0>--<232.0,803.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 12 | 8 | 53 | 474 | 21 | 377 | 0 |
| 1% | 1% | 6% | 50% | 2% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
