# Cube World

# Link: https://alexandervanbibber.github.io/Computer-Graphics-Project-2/

This is a map of The Legend of Zelda: Breath of the Wild reconstructed using cubes.

# Controls:

Left/Right Arrow Keys: Rotate the camera around the z-axis of the map

Up/Down Arrow Keys: Rotate the camera around the x-axis of the map (If you go far enough the entire map flips and becomes a mirrored version of itself)

Enter: Turn on the bezier curve display (You must refresh the page to turn them off)

# Design

I got the height map here: https://www.reddit.com/r/gamedev/comments/ijicoi/i_found_a_4k_heightmap_of_the_botw_world_if/?solution=5c6626a3ae8696d25c6626a3ae8696d2&js_challenge=1&jsc_token=2824be10929bdc604753c70a67a1c33197b45ec2326ae8c559ac969adae7597c&jsc_orig_r=

I got the color map here: https://objmap.zeldamods.org/#/map/z3,0,0

I used an online photo editing tool to overlay the color and height maps on top of each other, and then trimmed them to be the same dimensions.

I then ran both images through a PNG to pixel translator so that they would map onto the cube grid cleanly.

# AI Usage:

I used Claude a lot for creating the cubes that make up the dragon, and having them follow the bezier curve without changing their relative positions. 

I also used Claude to help me store the image data from PNGs into an array to project onto my cube grid.
