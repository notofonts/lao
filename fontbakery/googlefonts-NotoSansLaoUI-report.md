## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansLaoUI/googlefonts/ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Lao UI' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[14] NotoSansLaoUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?)

	* r (U+0072): X=311.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=363.0,Y=-1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=490.5,Y=-0.5 (should be at baseline 0?) 

	* 32 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansLaoUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 581 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=386.0,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=542.5,Y=1.0 (should be at baseline 0?)

	* c (U+0063): X=402.5,Y=1.0 (should be at baseline 0?)

	* e (U+0065): X=435.0,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=349.5,Y=534.5 (should be at x-height 536?)

	* h (U+0068): X=292.5,Y=537.0 (should be at x-height 536?)

	* m (U+006D): X=281.0,Y=534.5 (should be at x-height 536?)

	* m (U+006D): X=480.5,Y=535.0 (should be at x-height 536?)

	* m (U+006D): X=619.0,Y=535.5 (should be at x-height 536?)

	* section (U+00A7): X=134.0,Y=0.5 (should be at baseline 0?) 

	* 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* W (U+0057): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* W (U+0057): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wacute (U+1E82): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wacute (U+1E82): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wacute (U+1E82): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wcircumflex (U+0174): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wcircumflex (U+0174): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wdieresis (U+1E84): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723 

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansLaoUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 583 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 319:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=388.0,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=490.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=543.5,Y=1.5 (should be at baseline 0?)

	* b (U+0062): X=297.0,Y=535.5 (should be at x-height 536?)

	* c (U+0063): X=409.5,Y=2.0 (should be at baseline 0?)

	* e (U+0065): X=443.0,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=343.5,Y=537.5 (should be at x-height 536?)

	* g (U+0067): X=398.0,Y=2.0 (should be at baseline 0?)

	* h (U+0068): X=236.5,Y=538.0 (should be at x-height 536?)

	* m (U+006D): X=292.5,Y=537.5 (should be at x-height 536?) 

	* 69 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<329.0,217.5>-<335.0,187.0>-<337.0,166.0>>/B<<337.0,166.0>-<340.0,187.0>-<345.5,217.0>> = 13.570434385161475

	* W (U+0057): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* W (U+0057): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wacute (U+1E82): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wacute (U+1E82): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wcircumflex (U+0174): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wcircumflex (U+0174): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wdieresis (U+1E84): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wdieresis (U+1E84): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wgrave (U+1E80): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475 

	* Wgrave (U+1E80): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansLaoUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=141.5,Y=1.5 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=1.5 (should be at baseline 0?)

	* comma (U+002C): X=72.0,Y=0.5 (should be at baseline 0?)

	* period (U+002E): X=141.5,Y=1.5 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=1.5 (should be at baseline 0?)

	* three (U+0033): X=136.5,Y=1.5 (should be at baseline 0?)

	* five (U+0035): X=149.5,Y=1.5 (should be at baseline 0?)

	* nine (U+0039): X=95.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=141.5,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=1.5 (should be at baseline 0?) 

	* 74 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<108.0,38.0>--<108.0,36.0>>

	* M (U+004D) contains a short segment L<<140.0,668.0>--<137.0,668.0>>

	* M (U+004D) contains a short segment L<<424.0,64.0>--<427.0,64.0>>

	* M (U+004D) contains a short segment L<<440.0,0.0>--<409.0,0.0>>

	* N (U+004E) contains a short segment L<<139.0,642.0>--<137.0,642.0>>

	* N (U+004E) contains a short segment L<<570.0,74.0>--<572.0,74.0>>

	* a (U+0061) contains a short segment L<<401.0,98.0>--<399.0,98.0>>

	* d (U+0064) contains a short segment L<<465.0,105.0>--<463.0,105.0>>

	* k (U+006B) contains a short segment L<<126.0,218.0>--<126.0,218.0>>

	* m (U+006D) contains a short segment L<<126.0,438.0>--<129.0,438.0>> 

	* 86 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansLaoUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=147.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=98.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=66.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=491.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=478.0,Y=2.0 (should be at baseline 0?)

	* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

	* c (U+0063): X=385.0,Y=535.0 (should be at x-height 536?)

	* e (U+0065): X=395.0,Y=-2.0 (should be at baseline 0?)

	* f (U+0066): X=111.0,Y=534.0 (should be at x-height 536?)

	* s (U+0073): X=118.0,Y=-0.5 (should be at baseline 0?) 

	* 50 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<127.0,55.0>--<127.0,53.0>>

	* at (U+0040) contains a short segment B<<602.0,317.0>-<601.0,299.0>-<600.5,282.5>>

	* at (U+0040) contains a short segment B<<600.5,282.5>-<600.0,266.0>-<600.0,252.0>>

	* M (U+004D) contains a short segment L<<154.0,653.0>--<151.0,653.0>>

	* M (U+004D) contains a short segment L<<434.0,89.0>--<437.0,89.0>>

	* N (U+004E) contains a short segment L<<153.0,624.0>--<150.0,624.0>>

	* N (U+004E) contains a short segment L<<575.0,92.0>--<578.0,92.0>>

	* Q (U+0051) contains a short segment B<<399.0,-9.5>-<391.0,-10.0>-<384.0,-10.0>>

	* a (U+0061) contains a short segment L<<401.0,90.0>--<398.0,90.0>>

	* d (U+0064) contains a short segment L<<458.0,93.0>--<455.0,93.0>> 

	* 78 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* soSeua-lao (U+0EAA): L<<479.0,83.0>--<478.0,327.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansLaoUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 575 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 321:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* slash (U+002F): X=110.0,Y=-2.0 (should be at baseline 0?)

	* slash (U+002F): X=9.0,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=136.0,Y=-1.0 (should be at baseline 0?)

	* nine (U+0039): X=98.0,Y=-1.0 (should be at baseline 0?)

	* at (U+0040): X=552.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=538.5,Y=-0.5 (should be at baseline 0?)

	* backslash (U+005C): X=377.0,Y=-2.0 (should be at baseline 0?)

	* backslash (U+005C): X=275.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=190.0,Y=534.5 (should be at x-height 536?)

	* c (U+0063): X=385.5,Y=-1.5 (should be at baseline 0?) 

	* 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wacute (U+1E82): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wcircumflex (U+0174): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wdieresis (U+1E84): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328 

	* Wgrave (U+1E80): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansLaoUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><br></div></details><details><summary><b>[14] NotoSansLaoUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 577 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=382.5,Y=0.5 (should be at baseline 0?)

	* three (U+0033): X=134.0,Y=-0.5 (should be at baseline 0?)

	* nine (U+0039): X=93.0,Y=-2.0 (should be at baseline 0?)

	* at (U+0040): X=435.0,Y=-1.0 (should be at baseline 0?)

	* C (U+0043): X=490.5,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=540.0,Y=0.5 (should be at baseline 0?)

	* S (U+0053): X=138.5,Y=-0.5 (should be at baseline 0?)

	* c (U+0063): X=393.5,Y=-0.5 (should be at baseline 0?)

	* e (U+0065): X=425.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=128.5,Y=-2.0 (should be at baseline 0?) 

	* 75 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wacute (U+1E82): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wcircumflex (U+0174): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wdieresis (U+1E84): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wgrave (U+1E80): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216 

	* khmuNyo-lao (U+0EDF): B<<312.5,231.5>-<286.0,252.0>-<282.0,285.0>>/L<<282.0,285.0>--<282.0,232.0>> = 6.911227119024662 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansLaoUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Lao UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSansLaoUI-MM[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Expected "NotoSansLaoUI[wdth,wght].ttf. Got NotoSansLaoUI-MM[wdth,wght].ttf. [code: bad-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Black.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Bold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-ExtraLight.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Light.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Medium.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Regular.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-SemiBold.ttf', 'fonts/NotoSansLaoUI/googlefonts/ttf/NotoSansLaoUI-Thin.ttf', 'fonts/NotoSansLaoUI/googlefonts/variable-ttf/NotoSansLaoUI-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* 🔥 **FAIL** The following glyph names do not comply with naming conventions: koKai-lao, khoKhai-lao, khoKhuay-lao, ngoNgu-lao, coCok-lao, soSang-lao, nyoNyung-lao, doDek-lao, toTa-lao, thoThong-lao and 98 more.

Use -F or --full-lists to disable shortening of long lists.

 A glyph name must be entirely comprised of characters from the following set: A-Z a-z 0-9 .(period) _(underscore). A glyph name must not start with a digit or period. There are a few exceptions such as the special glyph ".notdef". The glyph names "twocents", "a1", and "_" are all valid, while "2cents" and ".twocents" are not. [code: found-invalid-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- brevecomb

	- caroncomb

	- cedillacomb

	- circumflexcomb

	- commaaccentcomb

	- commaturnedabovecomb

	- dieresiscomb

	- dotaccentcomb

	- euVowel-lao 

	- 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 73 | 62 | 1171 | 62 | 935 | 0 |
| 0% | 3% | 3% | 51% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**