# Paul Friedl

I'm currently a JSD candidate at Humboldt University Berlin and an affiliate scholar at the Information Law Institute at New York University.

### text ###


/*
 * I add this to html files generated with pandoc.
 */

html {
  font-size: 100%;
  overflow-y: scroll;
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
}

body {
  color: #444;
  font-family: Georgia, Palatino, 'Palatino Linotype', Times, 'Times New Roman', serif;
  font-size: 12px;
  line-height: 1.7;
  padding: 1em;
  margin: auto;
  max-width: 42em;
  background: #fefefe;
}

a {
  color: #0645ad;
  text-decoration: none;
}

a:visited {
  color: #0b0080;
}

a:hover {
  color: #06e;
}

a:active {
  color: #faa700;
}

a:focus {
  outline: thin dotted;
}

*::-moz-selection {
  background: rgba(255, 255, 0, 0.3);
  color: #000;
}

*::selection {
  background: rgba(255, 255, 0, 0.3);
  color: #000;
}

a::-moz-selection {
  background: rgba(255, 255, 0, 0.3);
  color: #0645ad;
}

a::selection {
  background: rgba(255, 255, 0, 0.3);
  color: #0645ad;
}

p {
  margin: 1em 0;
}

img {
  max-width: 100%;
}

h1, h2, h3, h4, h5, h6 {
  color: #111;
  line-height: 125%;
  margin-top: 2em;
  font-weight: normal;
}

h4, h5, h6 {
  font-weight: bold;
}

h1 {
  font-size: 2.5em;
}

h2 {
  font-size: 2em;
}

h3 {
  font-size: 1.5em;
}

h4 {
  font-size: 1.2em;
}

h5 {
  font-size: 1em;
}

h6 {
  font-size: 0.9em;
}

blockquote {
  color: #666666;
  margin: 0;
  padding-left: 3em;
  border-left: 0.5em #EEE solid;
}

hr {
  display: block;
  height: 2px;
  border: 0;
  border-top: 1px solid #aaa;
  border-bottom: 1px solid #eee;
  margin: 1em 0;
  padding: 0;
}

pre, code, kbd, samp {
  color: #000;
  font-family: monospace, monospace;
  _font-family: 'courier new', monospace;
  font-size: 0.98em;
}

pre {
  white-space: pre;
  white-space: pre-wrap;
  word-wrap: break-word;
}

b, strong {
  font-weight: bold;
}

dfn {
  font-style: italic;
}

ins {
  background: #ff9;
  color: #000;
  text-decoration: none;
}

mark {
  background: #ff0;
  color: #000;
  font-style: italic;
  font-weight: bold;
}

sub, sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sup {
  top: -0.5em;
}

sub {
  bottom: -0.25em;
}

ul, ol {
  margin: 1em 0;
  padding: 0 0 0 2em;
}

li p:last-child {
  margin-bottom: 0;
}

ul ul, ol ol {
  margin: .3em 0;
}

dl {
  margin-bottom: 1em;
}

dt {
  font-weight: bold;
  margin-bottom: .8em;
}

dd {
  margin: 0 0 .8em 2em;
}

dd:last-child {
  margin-bottom: 0;
}

img {
  border: 0;
  -ms-interpolation-mode: bicubic;
  vertical-align: middle;
}

figure {
  display: block;
  text-align: center;
  margin: 1em 0;
}

figure img {
  border: none;
  margin: 0 auto;
}

figcaption {
  font-size: 0.8em;
  font-style: italic;
  margin: 0 0 .8em;
}

table {
  margin-bottom: 2em;
  border-bottom: 1px solid #ddd;
  border-right: 1px solid #ddd;
  border-spacing: 0;
  border-collapse: collapse;
}

table th {
  padding: .2em 1em;
  background-color: #eee;
  border-top: 1px solid #ddd;
  border-left: 1px solid #ddd;
}

table td {
  padding: .2em 1em;
  border-top: 1px solid #ddd;
  border-left: 1px solid #ddd;
  vertical-align: top;
}

.author {
  font-size: 1.2em;
  text-align: center;
}

@media only screen and (min-width: 480px) {
  body {
    font-size: 14px;
  }
}
@media only screen and (min-width: 768px) {
  body {
    font-size: 16px;
  }
}
@media print {
  * {
    background: transparent !important;
    color: black !important;
    filter: none !important;
    -ms-filter: none !important;
  }

  body {
    font-size: 12pt;
    max-width: 100%;
  }

  a, a:visited {
    text-decoration: underline;
  }

  hr {
    height: 1px;
    border: 0;
    border-bottom: 1px solid black;
  }

  a[href]:after {
    content: " (" attr(href) ")";
  }

  abbr[title]:after {
    content: " (" attr(title) ")";
  }

  .ir a:after, a[href^="javascript:"]:after, a[href^="#"]:after {
    content: "";
  }

  pre, blockquote {
    border: 1px solid #999;
    padding-right: 1em;
    page-break-inside: avoid;
  }

  tr, img {
    page-break-inside: avoid;
  }

  img {
    max-width: 100% !important;
  }

  @page :left {
    margin: 15mm 20mm 15mm 10mm;
}

  @page :right {
    margin: 15mm 10mm 15mm 20mm;
}

  p, h2, h3 {
    orphans: 3;
    widows: 3;
  }

  h2, h3 {
    page-break-after: avoid;
  }
}
