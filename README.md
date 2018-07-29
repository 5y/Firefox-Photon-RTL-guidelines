<p align="center">
<img width="200" src="/static/sadi-eng.jpg" alt="Firefox Photon RTL guidelineslogo">
<img width="200" src="/static/Sadi-Persian.jpg" alt="Firefox Photon RTL guidelineslogo"></a></p>
<h6 align="center"><a href="https://en.wikipedia.org/wiki/Saadi_Shirazi">Saadi Shirazi</a></h6s>
</p>
<div align="center">
<h1 align="center">Firefox Photon RTL/BiDi guideline
</h1>
</div>

# Bidirectional Scripts
<p>Bidirectional Scripts is written from right to left  except for the number,  such as Hebrew, Yiddish, Judezmo, Arabic, Persian, Urdu, Pashto, Sindhi, Kurdish, Syriac, Dhivehi.</p> 


 - RTL : RTL languages display content from right to left.
 - LTR:  LTR languages display content from left to right.
 
<p> UIs for languages that are read from right-to-left (RTL) should be mirrored to ensure content is easy to understand. </p>


→ Bidirectional (e.g. نشاید که نامد نهد آدمی )

← Directional    	(e.g. Hello World )

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
	- LTR strings and words.
	- URL ( even included some RTL characters).
	-  Numbers
	
		
|  Correct  |Wrong   |
|--|--|
| <img src="https://user-images.githubusercontent.com/1941933/41205819-b44c3842-6d0f-11e8-81d0-506960e5ee40.png" width="200">|<img src="https://user-images.githubusercontent.com/1941933/41205881-b63b8e40-6d10-11e8-87a2-c297e9094198.jpg" width="200">


(Figure 2 , Text and numbers should always be in the correct direction for the language.)



# How to change LRT to RTL?
- None RTL languages text aligned to the right.



- Text filed icon aligned to opposite side.

|  RTL  |LTR   |
|--|--|
| <img src="https://wopr.norad.org/~fxios/screenshots/fxios/v12/fa/fa/iPhone%208-04Settings-AddCustomSearchSettings-0.png" width="200"> |<img src="https://wopr.norad.org/~fxios/screenshots/fxios/v12/en-US/en-US/iPhone%208-04Settings-AddCustomSearchSettings-0.png" width="200">
- Navigation buttons ( such as Firefox for iOS intro ) are displayed in reverse order.



|  RTL  |LTR   |
|--|--|
| <img src="https://user-images.githubusercontent.com/1941933/41205924-b4a3e77a-6d11-11e8-96a0-21074aac7f38.png" width="200"> |<img src="https://user-images.githubusercontent.com/1941933/41205928-c4707290-6d11-11e8-85ea-88db8d3d69ba.png" width="200">
|Swipe to the Right |Swipte to the Left |

- Menu and all icons that communicate direction are mirrored.


|  RTL  |LTR   |
|--|--|
| <img src="https://wopr.norad.org/~fxios/screenshots/fxios/v12/fa/fa/iPhone%208-03MenuOnTopSites-01.png" width="200"> |<img src="https://wopr.norad.org/~fxios/screenshots/fxios/v12/en-US/en-US/iPhone%208-03MenuOnTopSites-01.png" width="200">

- Text translated to the RTL languages is always aligned to the right.



![image](https://user-images.githubusercontent.com/1941933/38196754-f8284792-3699-11e8-9090-f37934d8261c.png) 
*Figure source : Behdad Esfahbod* 

- Numbers such as phone, clock, keyboard and etc are the same position. However, they have different shape.

|  RTL  |LTR   |
|--|--|
| <img src="https://user-images.githubusercontent.com/1941933/43368754-8c6d96e8-9377-11e8-91cb-2f1ed205ff22.png" width="200"> |<img src="https://user-images.githubusercontent.com/1941933/43368776-daf2b8de-9377-11e8-950c-989e3b7e8236.png" width="200">

- Navigation buttons such as Back and Forward arrows are mirrored. Also, other icons that  communicate direction.

|  RTL  |LTR   |
|--|--|
| <img src="https://user-images.githubusercontent.com/1941933/43369039-feab0dea-937b-11e8-84c0-2f9fbead9e58.png" width="200"> |<img src="https://user-images.githubusercontent.com/1941933/43369050-299cecda-937c-11e8-8350-c7f104ae51ec.png" width="200">
