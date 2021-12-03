# "Extra wide" ergonomic layout for non-split keyboards

Standard keyboards are common and uncomfortable. Pondering this, I remembered how Colemak users have developed a "wide" layout, where the right hand is shifted one key to the right, to reduce strain on the wrists. (http://colemakmods.github.io/ergonomic-mods/wide.html) So, I had the idea to go even further, and shift the left hand one key to the left as well. Since this means there is no left pinky shift, caps lock, or tab, I had to put them somewhere. The newly-freed middle columns are one natural place, so I decided to mimic the default layout of the Model01 (https://shop.keyboard.io/products/model-01-keyboard), since my partner has one and it looks cool. With that decided, I went ahead and made this layout resemble the Model01 layout to a large degree. The exceptions are that there is a row of (home, page down, page up, end) right below the arrow keys, the hyphen, backslash, and backtick are in different places since that's where they fit, I added a super key, caps lock, and compose keys, and of course the thumb keys are different and there's no palm key. One final feature, again borrowed from the Colemak community: the "angle mod", where the lowest row of keys for the left hand are shifted to the left so that keys pressed with a single finger are lined up with the finger's motion (http://colemakmods.github.io/ergonomic-mods/angle.html).

## ASCII Art layout

```
esc
1   2   3   4   5  sup lock 6   7   8   9   0   -_  =+___
__q   w   f   p   b  `~ multi j   l   u   y;   \|  multi_
____a   r   s   t   g  tab ret  m   n   e   i   o   '"___
______x   c   d   v   z  esc ret  k   h   ,<  .>  /?_____
fn  ^ m01fn bkspc ______shift______  spc  alt  ^
```

The "m01fn" key is like the "fn" key on the Model01. Holding it down changes the keys on the right hand. In combination with the original escape key, it switches between Colemak-DH and QWERTY.

```
colemak/qwerty
_   _   _   _   _   _   _   _   _   _   _   _   _   _____
___   _   _   _   _   _   _   _   {   }   [   ]   _   ___
_____   _   _   _   _   _   _   <-  v   ^  ->   _    ____
_______   _   _   _   _   _   _  home pgdn pgup end _____
_  _  m01fn   _   __________________   _    _   _
```
