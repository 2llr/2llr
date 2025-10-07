---
@
---

```mermaid
flowchart TD

subgraph 息子
a1[起床]-->a2{朝食}
a2awefeawef-->|急いでいない場合|a3[テレビ視聴]-->a4[歯磨き]
a2-->|急いでいる場合|a4
a4-->a5[支度]-aaefawef->a6[出発]
end

subgraph 母
b1[起床]-->b2[朝食準備]-->b3[朝食]-->b4[朝食片づけ]
end
```

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
```

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.


$$1+2\left($$

<!-- a -->
<a draggable="true">hello</a>
<a href="a.png" download>download</a>

<!-- abbr -->
<abbr>CSS</abbr> (Cascading Style Sheets)

<!-- acronym -->
<acronym title="World Wide Web">WWW</acronym>

<!-- address -->
<address>
  <a href="mailto:jim@example.com">jim@example.com</a><br />
  <a href="tel:+14155550132">+1 (415) 555‑0132</a>
</address>

<!-- area -->
<map name="infographic">
  <area
    shape="poly"
    coords="129,0,260,95,129,138"
    href="https://developer.mozilla.org/docs/Web/HTTP"
    alt="HTTP" />
  <area
    shape="poly"
    coords="260,96,209,249,130,138"
    href="https://developer.mozilla.org/docs/Web/HTML"
    alt="HTML" />
  <area
    shape="poly"
    coords="209,249,49,249,130,139"
    href="https://developer.mozilla.org/docs/Web/JavaScript"
    alt="JavaScript" />
  <area
    shape="poly"
    coords="48,249,0,96,129,138"
    href="https://developer.mozilla.org/docs/Web/API"
    alt="Web APIs" />
  <area
    shape="poly"
    coords="0,95,128,0,128,137"
    href="https://developer.mozilla.org/docs/Web/CSS"
    alt="CSS" />
</map>

<!-- article -->
<article class="forecast">
  <h1>シアトルの天気予報</h1>
  <article class="day-forecast">
    <h2>2018/03/03</h2>
    <p>雨。</p>
  </article>
  <article class="day-forecast">
    <h2>2018/03/04</h2>
    <p>ずっと雨。</p>
  </article>
  <article class="day-forecast">
    <h2>2028/03/05</h2>
    <p>大雨。</p>
  </article>
</article>

<!-- aside -->
<aside>
  <p>サメハダイモリは、致命的な神経毒で身を守ります。</p>
</aside>

<!-- audio -->
<figure>
  <figcaption>T-Rex の声を聴こう:</figcaption>
  <audio controls src="/shared-assets/audio/t-rex-roar.mp3"></audio>
  <a href="/shared-assets/audio/t-rex-roar.mp3"> Download audio </a>
</figure>


<blockquote cite="https://datatracker.ietf.org/doc/html/rfc1149">
  <p>
    Avian carriers can provide high delay, low throughput, and low altitude
    service. The connection topology is limited to a single point-to-point path
    for each carrier, used with standard carriers, but many carriers can be used
    without significant interference with each other, outside early spring. This
    is because of the 3D ether space available to the carriers, in contrast to
    the 1D ether used by IEEE802.3. The carriers have an intrinsic collision
    avoidance system, which increases availability.
  </p>
</blockquote>

<button accesskey="s">Stress reliever</button>


<fencedframe src="https://example.com" width="300" height="200"></fencedframe>

<p contenteditable dir="rtl">abcdefg</p>

<textarea spellcheck="true">
This exampull will be checkd fur spellung when you try to edit it.
</textarea>

<p dir="rtl" autofocus>abcdefg</p>

<kbd>hello</kbd>

[site]: https://example.com
[docs]: https://example.com/docs

See the [docs] or visit the [site].

[^policy]: This project follows XYZ policy.

We comply with the policy[^policy].


We comply with the policy[^policyaaa].

<picture>
  <source srcset="./assets/hints-desktop.png" media="(hover: hover) and (pointer: fine)">
  <source srcset="./assets/hints-touch.png"   media="(hover: none) and (pointer: coarse)">
  <img src="./assets/hints-generic.png" alt="Usage hints">
</picture>

<marquee>ABC</marquee>

