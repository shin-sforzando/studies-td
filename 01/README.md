## 001: Flying Butterfly

Ever since I found the images of the three butterflies in the TouchDesigner sample file, I wondered what these would be used for.
First, let's make a butterfly flapping its wings.

![Flying Butterfly](https://user-images.githubusercontent.com/32637762/120374305-5d9a6200-c354-11eb-9e71-87c6e1599bd3.png)

### Used operators in this study

#### Object Components (3D objects for rendering)

- Camera COMP
- Geometry COMP
- Light COMP

#### Panel Components (interactive 2D panels)

- Button COMP

#### TOP

- Movie File In
- Movie File Out
- Null
- Out
- Render

#### CHOP

- Count
- Info
- LFO
- Math
- Null

#### SOP

- Texture
- Trace
- Twist

#### MAT

- Phong

#### DAT

- Table
- Select

### Memo

Trace OP is just amazing.
However, it creates some garbage points.
I'll do more research on how to remove them.

Twist OP selects two axes to twist.
It's counter-intuitive that the axis I didn't choose should be the center.
In this case, the Z axis is selected as Primary, and the X axis is selected as Secondary.

I struggled to get a row from Table.
There seems to be a better way.
