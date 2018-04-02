<p align="center">
<img width="200" src="/static/sadi-eng.jpg" alt="Firefox Photon RTL guidelineslogo">
<img width="200" src="/static/Sadi-Persian.jpg" alt="Firefox Photon RTL guidelineslogo"></a></p>
<h6 align="center"><a href="https://en.wikipedia.org/wiki/Saadi_Shirazi">Saadi Shirazi</a></h6s>
</p>
<div align="center">
<h1 align="center">Firefox Photon RTL/BiDi guideline
</h1>
</div>

## Bidirectional Scripts
<p>Bidirectional Scripts is written from right to left  except for the number,  such as Hebrew, Yiddish, Judezmo, Arabic, Persian, Urdu, Pashto, Sindhi, Kurdish, Syriac, Dhivehi.</p>


 - RTL : RTL languages display content from right to left.
 - LTR:  LTR languages display content from left to right.

<p> UIs for languages that are read from right-to-left (RTL) should be mirrored to ensure content is easy to understand. </p>

→ Bidirectional

<p> RTL content also affects the direction in which some icons and images are displayed, particularly those depicting a sequence of events.</p>
<p>In general, the passage of time is depicted as left to right for LTR languages, and right to left for RTL languages.</p>


| Element | LTR | RTL
|--|--|--|
|Text| Sentences are read from left to right. |Sentences are read from right to left.
|Timeline|	An illustrated sequence of events progresses left to right. |An illustrated sequence of events progresses right to left.
|Imagery|	An arrow pointing left to right indicates forward motion: → |An arrow pointing right to left indicates forward motion: ←
----------

# RTL UI overview

- What is **mirroring** ?
	- When a UI is changed from LTR to RTL (or vice-versa), it’s often called **mirroring**.  An RTL layout is the mirror image of an LTR layout, and it affects layout, text, and graphics.
	
	
		
|  LTR |RTL  |
|--|--|
| <img src="https://user-images.githubusercontent.com/1941933/38197490-a1ce98ac-369d-11e8-88af-e237b1412953.png" width="200">|<img src="https://user-images.githubusercontent.com/1941933/38205860-68fcf0b2-36bd-11e8-87b6-849628769508.png" width="200">

(Figure 1 , Mirroring Example)

	 
- Following Item are not **mirrored**:
