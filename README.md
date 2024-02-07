#Come to the place with socks
#If this box is, then open
Take the nearest sock in the left hand from the drawer
Do(when "In the left hand sock will not look like the right")
    If the socks in the shelf & in drower = 0
        then this is your ninja way(without socks)
    Take the nearest sock in your right hand
    If two mismatched socks
        then find a place called "shelf"
        put a sock from the right hand into the shelf
    If the socks in drawer = 0 & in the shelf > 1
        sock from left hand thrown in trash
        all socks are transfered to the "box"
        takes the closest sock into the left hand
