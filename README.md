#### Colors Repo
  - This repo is a small subset of my colour collection for Github
  - Keep it simple, generally only using 9 colors. There are a few with some bolds  
  - There's a color file seperate from .Xresources for cleaner switching. Include the file with 
    ` #include </path/to/crayolo/colors/[file]> `
  - Added matching walls directory
  - Random color script will display associated wall if exists, else a pattern wall using colors from xrdb

#### Implementation
  - Use below in your .Xresources file 
  ```
  #include </path/to/crayolo/colors/[file]>  
    
  .... other xresource code goes here  
    
  ! Colors  
  *background:   bg  
  *foreground:   fg  
  *color0:      blk  
  *color8:      bblk  
  *color1:      red  
  *color9:      bred  
  *color2:      grn  
  *color10:     bgrn  
  *color3:      ylw  
  *color11:     bylw  
  *color4:      blu  
  *color12:     bblu  
  *color5:      mag  
  *color13:     bmag  
  *color6:      cyn  
  *color14:     bcyn  
  *color7:      wht  
  *color15:     bwht  
```
#### Miscellaneous
  - Added tile.xbm to the repo [IIRC, I got this off of dcat's github at some point]
  - Implementation Example ` xetroot -bitmap $walls/tile.xbm -bg "$(xrdb -query | grep  "*background" | awk '{print $2}')" -fg "$(xrdb -query | grep  "*foreground" | awk '{print $2}')" `
  - use random color picker to get a different color at each wm-start. Place in .xinitrc, or wm config, I suppose
  - Find me on linuxbbq, forum or IRC on freenode (I'm a weekend warrior)

#### Previews

###### [bluetype](colors/bluetype)
![bluetype](preview/bluetype.png)
###### [simplicity](colors/simplicity)
![simplicity](preview/simplicity.png)
###### [sprout](colors/sprout)
![sprout](preview/sprout.png)
###### [raild](colors/raild)
![raild](preview/raild.png)
###### [tealights](colors/tealights)
![tealights](preview/tealights.png)
###### [traffic](colors/traffic)
![traffic](preview/traffic.png)
###### [prevail](colors/prevail)
![prevail](preview/prevail.png)
###### [blumune](colors/blumune)
![blumune](preview/blumune.png)
###### [soundwave](colors/soundwave)
![soundwave](preview/soundwave.png)
###### [coco](colors/coco)
![coco](preview/coco.png)
###### [blend](colors/blend)
![blend](preview/blend.png)
###### [link](colors/link)
![link](preview/link.png)
###### [view](colors/view)
![view](preview/view.png)
###### [kit](colors/kit)
![kit](preview/kit.png)
###### [corduroy](colors/corduroy)
![corduroy](preview/corduroy.png)
###### [shade](shade)
![shade](preview/shade.png)
###### [skigh](colors/skigh)
![skigh](preview/skigh.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_skigh.png)
###### [5725](colors/5725)
![5725](preview/5725.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_5725.png)
###### [flapr](colors/flapr)
![flapr](preview/flapr.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_flapr.png)
###### [brownstone](colors/brownstone)
![brownstone](preview/brownstone.png)
###### [slate](colors/slate)
![slate](preview/slate.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_slate.png)
###### [vans](colors/vans)
![vans](preview/vans.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_vans.png)
###### [fendr](colors/fendr)
![fendr](preview/fendr.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_fendr.png)
###### [owl](colors/owl)
![owl](preview/owl.png)
###### [sundr](colors/sundr)
![sundr](preview/sundr.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_sundr.png)
###### [chaires](colors/chaires)
![chaires](preview/chaires.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_chaires.png)
###### [spire](colors/spire)
![spire](preview/spire.png)
###### [urban](colors/urban)
![urban](preview/urban.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_urban.png)
###### [zent](colors/zent)
![blok](preview/blok.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_zent.png)
###### [diner](colors/diner)
![diner](preview/diner.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_diner.png)
###### [provrb](colors/provrb)
![provrb](preview/provrb.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_proverbial.png)
###### [petal](colors/petal)
![petal](preview/petal.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_petal.png)
###### [paints](colors/paints)
![paints](preview/paints.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_paints.png)
###### [book](colors/book)
![book](preview/book.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_book.png)
###### [parkd](colors/parkd)
![parkd](preview/parkd.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_parkd.png)
###### [relax](colors/relax)
![relax](preview/relax.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_relax.png)
###### [raiin](colors/raiin)
![raiin](preview/raiin.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_raiin.png)
###### [bulb](colors/bulb)
![bulb](preview/bulb.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_bulb.png)
###### [novembr](colors/novembr)
![novembr](preview/novmbr.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_novmbr.png)
###### [branch](colors/branch)
![branch](preview/branch.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_autm.png)
###### [wintry](colors/wintry)
![wintry](preview/wintry.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_wintrymix.png)
###### [escen](colors/escen)
![escen](preview/escen.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_headphones.png)
###### [fury](colors/fury)
![fury](preview/fury.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_illusion.png)
###### [squarees](colors/squarees)
![squarees](preview/squares.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_squares.png)
###### [harbing](colors/harbing)
![harbing](preview/harbing.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_harbing.png)
###### [poly](colors/poly)
![poly](preview/poly.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_poly.png)
###### [victory](colors/victory)
![victory](preview/victory.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_victory.png)
###### [bark](colors/bark)
![bark](preview/bark.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_bark.png)
###### [scape](colors/scape)
![scape](preview/scape.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_minus2b.png)
###### [depth](colors/depth)
![depth](preview/depth.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_mail.png)
###### [scag](colors/scag)
![scag](preview/scag.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_simple.png)
###### [leaf](colors/leaf)
![leaf](preview/leaf.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_exposed.png)
###### [designr](colors/designr)
![designr](preview/designr.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_designr.png)
###### [mattd](colors/mattd)
![mattd](preview/mattd.png)
![git_tag](https://github.com/dkeg/scrots/blob/master/_wavr.png)
