Name: Oier Perez


Additional notes:

The demo is about fox following xbot. In this case the fox uses a 1Dblend tree in order to swap between Idle, Walk and Run state(the transition between walk and run is not
very notizable maybe due to animation data). On the other hand, xbot is using a 2D blend tree to decide its looking direction. The model by default is always looking on the +X 
direction. Modifications can be set up on the blend tree for both the fox and the xbot, like changing the animation of each node. If the program is running slow reduce the 
number of shadow neightbours that are taking into account for the shadows of sponza in the graphics settings GUI. Apart from that, a free camera mode is supported. In order to
swap between the 3rd person or the free camera press left CTRL. Enjoy!

Known bugs: 

Parameters out of the triangulation will make the program crash. This can only happen if they are set by brutforce on the tree editor.
