<h1><img width="64" height="64" src="resources/icon.png"/> Minimal-Blue And Minimal-Black Themes</h1>

A very lite-weight, quick to render and compatible with every screen-size,<br/>
any resolution and any pixel-density<br/>
(even if you force one using <code>--force-device-scale-factor=1.4</code> for example)<br/>

<br/><img src="resource/screenshot_1_1.png" />
<br/><img src="resource/screenshot_1_2.png" />
<br/><img src="resource/screenshot_2.png"   />

<hr/>
Notes:

<code>manifest_attribute_complete.json</code> is a dictionary code for all valid-attributes for a theme-manifest file.

The blue one is the minimal one<br/>
the black theme, has a small addition:
<pre>
  "frame"                            : [ 66, 116, 201, 1]
, "frame_inactive"                   : [152, 188, 233, 1]
</pre>

You should compile to CRX using Chrome developer-mode.br</>
installation is done by drag&drop over the <code>chrome://extensions</code> tab.<br/>

You can tryout the themes by downloading either one from the <code>__BINARY__</code> folder.
