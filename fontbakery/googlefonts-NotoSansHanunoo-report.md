## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[7] NotoSansHanunoo-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/hanunoo.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansHanunoo/googlefonts/ttf/NotoSansHanunoo-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/hanunoo.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">᜵᜶</span> (Sylistic alternates)</li>


<pre>{'features': {'salt': True}}</pre>



<pre>Expected: uni1735.alt|uni1736.alt</pre>



<pre>Got     : uni1735|uni1736</pre>



<pre>                 ++++        ++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 817 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M18.0,-139.0L222.0,750.0L292.0,750.0L87.0,-139.0L18.0,-139.0Z"  transform="translate(0, 793)"/>
<path d="M18.0,-139.0L222.0,750.0L292.0,750.0L87.0,-139.0L18.0,-139.0ZM177.0,-139.0L381.0,750.0L451.0,750.0L246.0,-139.0L177.0,-139.0Z"  transform="translate(329, 793)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ᜲᜠ</span> (Ensure we're actually going through the USE!)</li>


<pre>Expected: uni25CC=0+594|uni1732=0@-14,-112+0|uni1722=1+521</pre>



<pre>Got     : uni25CC=0+594|uni1732=0@-14,-112+0|uni1720=1+880</pre>



<pre>                                                   ^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1474 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M323.0,514.0Q323.0,487.0 297.0,487.0Q271.0,487.0 271.0,514.0Q271.0,540.0 297.0,540.0Q323.0,540.0 323.0,514.0ZM408.0,496.0Q408.0,470.0 383.0,470.0Q355.0,470.0 355.0,496.0Q355.0,523.0 383.0,523.0Q408.0,523.0 408.0,496.0ZM239.0,496.0Q239.0,470.0 212.0,470.0Q186.0,470.0 186.0,496.0Q186.0,523.0 212.0,523.0Q239.0,523.0 239.0,496.0ZM480.0,448.0Q480.0,422.0 455.0,422.0Q428.0,422.0 428.0,448.0Q428.0,475.0 455.0,475.0Q480.0,475.0 480.0,448.0ZM167.0,448.0Q167.0,422.0 140.0,422.0Q114.0,422.0 114.0,447.0Q114.0,475.0 140.0,475.0Q167.0,475.0 167.0,448.0ZM529.0,376.0Q529.0,349.0 502.0,349.0Q476.0,349.0 476.0,376.0Q476.0,402.0 503.0,402.0Q529.0,402.0 529.0,376.0ZM118.0,376.0Q118.0,349.0 93.0,349.0Q65.0,349.0 65.0,376.0Q65.0,402.0 92.0,402.0Q118.0,402.0 118.0,376.0ZM546.0,291.0Q546.0,265.0 521.0,265.0Q494.0,265.0 494.0,291.0Q494.0,317.0 521.0,317.0Q546.0,317.0 546.0,291.0ZM101.0,291.0Q101.0,265.0 75.0,265.0Q48.0,265.0 48.0,291.0Q48.0,317.0 75.0,317.0Q101.0,317.0 101.0,291.0ZM529.0,206.0Q529.0,180.0 502.0,180.0Q476.0,180.0 476.0,206.0Q476.0,233.0 502.0,233.0Q529.0,233.0 529.0,206.0ZM118.0,206.0Q118.0,180.0 92.0,180.0Q65.0,180.0 65.0,206.0Q65.0,233.0 92.0,233.0Q118.0,233.0 118.0,206.0ZM480.0,133.0Q480.0,107.0 455.0,107.0Q428.0,107.0 428.0,133.0Q428.0,160.0 455.0,160.0Q480.0,160.0 480.0,133.0ZM167.0,133.0Q167.0,107.0 140.0,107.0Q114.0,107.0 114.0,133.0Q114.0,160.0 140.0,160.0Q167.0,160.0 167.0,133.0ZM408.0,85.0Q408.0,60.0 383.0,60.0Q355.0,60.0 355.0,85.0Q355.0,112.0 383.0,112.0Q408.0,112.0 408.0,85.0ZM239.0,87.0Q239.0,60.0 212.0,60.0Q186.0,60.0 186.0,85.0Q186.0,112.0 212.0,112.0Q239.0,112.0 239.0,87.0ZM323.0,69.0Q323.0,42.0 297.0,42.0Q271.0,42.0 271.0,69.0Q271.0,95.0 297.0,95.0Q323.0,95.0 323.0,69.0Z"  transform="translate(0, 793)"/>
<path d="M-409.0,732.0L-393.0,800.0L-103.0,800.0L-119.0,732.0L-409.0,732.0Z"  transform="translate(580, 681)"/>
<path d="M143.0,0.0L253.0,478.0L31.0,369.0L52.0,459.0L218.0,540.0Q237.0,549.0 254.5,554.0Q272.0,559.0 289.0,559.0Q312.0,559.0 322.0,544.0Q332.0,529.0 332.0,511.0Q332.0,483.0 323.0,442.0Q314.0,401.0 297.0,327.0L271.0,216.0Q264.0,187.0 257.0,158.5Q250.0,130.0 239.0,93.0Q263.0,111.0 289.5,133.0Q316.0,155.0 341.0,175.0Q420.0,241.0 501.5,318.0Q583.0,395.0 662.0,476.0Q741.0,557.0 810.0,634.0L906.0,634.0Q838.0,559.0 757.0,473.0Q676.0,387.0 587.0,300.0Q498.0,213.0 405.5,135.0Q313.0,57.0 222.0,0.0L143.0,0.0Z"  transform="translate(594, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1115 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M323.0,514.0Q323.0,487.0 297.0,487.0Q271.0,487.0 271.0,514.0Q271.0,540.0 297.0,540.0Q323.0,540.0 323.0,514.0ZM408.0,496.0Q408.0,470.0 383.0,470.0Q355.0,470.0 355.0,496.0Q355.0,523.0 383.0,523.0Q408.0,523.0 408.0,496.0ZM239.0,496.0Q239.0,470.0 212.0,470.0Q186.0,470.0 186.0,496.0Q186.0,523.0 212.0,523.0Q239.0,523.0 239.0,496.0ZM480.0,448.0Q480.0,422.0 455.0,422.0Q428.0,422.0 428.0,448.0Q428.0,475.0 455.0,475.0Q480.0,475.0 480.0,448.0ZM167.0,448.0Q167.0,422.0 140.0,422.0Q114.0,422.0 114.0,447.0Q114.0,475.0 140.0,475.0Q167.0,475.0 167.0,448.0ZM529.0,376.0Q529.0,349.0 502.0,349.0Q476.0,349.0 476.0,376.0Q476.0,402.0 503.0,402.0Q529.0,402.0 529.0,376.0ZM118.0,376.0Q118.0,349.0 93.0,349.0Q65.0,349.0 65.0,376.0Q65.0,402.0 92.0,402.0Q118.0,402.0 118.0,376.0ZM546.0,291.0Q546.0,265.0 521.0,265.0Q494.0,265.0 494.0,291.0Q494.0,317.0 521.0,317.0Q546.0,317.0 546.0,291.0ZM101.0,291.0Q101.0,265.0 75.0,265.0Q48.0,265.0 48.0,291.0Q48.0,317.0 75.0,317.0Q101.0,317.0 101.0,291.0ZM529.0,206.0Q529.0,180.0 502.0,180.0Q476.0,180.0 476.0,206.0Q476.0,233.0 502.0,233.0Q529.0,233.0 529.0,206.0ZM118.0,206.0Q118.0,180.0 92.0,180.0Q65.0,180.0 65.0,206.0Q65.0,233.0 92.0,233.0Q118.0,233.0 118.0,206.0ZM480.0,133.0Q480.0,107.0 455.0,107.0Q428.0,107.0 428.0,133.0Q428.0,160.0 455.0,160.0Q480.0,160.0 480.0,133.0ZM167.0,133.0Q167.0,107.0 140.0,107.0Q114.0,107.0 114.0,133.0Q114.0,160.0 140.0,160.0Q167.0,160.0 167.0,133.0ZM408.0,85.0Q408.0,60.0 383.0,60.0Q355.0,60.0 355.0,85.0Q355.0,112.0 383.0,112.0Q408.0,112.0 408.0,85.0ZM239.0,87.0Q239.0,60.0 212.0,60.0Q186.0,60.0 186.0,85.0Q186.0,112.0 212.0,112.0Q239.0,112.0 239.0,87.0ZM323.0,69.0Q323.0,42.0 297.0,42.0Q271.0,42.0 271.0,69.0Q271.0,95.0 297.0,95.0Q323.0,95.0 323.0,69.0Z"  transform="translate(0, 793)"/>
<path d="M-409.0,732.0L-393.0,800.0L-103.0,800.0L-119.0,732.0L-409.0,732.0Z"  transform="translate(580, 681)"/>
<path d="M115.0,0.0L411.0,294.0L129.0,294.0L129.0,345.0L300.0,494.0Q315.0,507.0 331.0,520.5Q347.0,534.0 365.0,547.0Q346.0,544.0 331.0,542.5Q316.0,541.0 300.0,541.0Q251.0,541.0 203.0,548.5Q155.0,556.0 117.0,571.0L143.0,634.0Q184.0,624.0 224.5,617.5Q265.0,611.0 332.0,611.0Q382.0,611.0 432.5,617.0Q483.0,623.0 523.0,634.0L523.0,594.0L255.0,362.0L523.0,362.0L523.0,304.0L213.0,0.0L115.0,0.0Z"  transform="translate(594, 793)"/>
</svg>


</div> [code: shaping-regression]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 uni1734 (U+1734) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+1734 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* And 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 6 | 110 | 7 | 103 | 0 |
| 0% | 0% | 3% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
