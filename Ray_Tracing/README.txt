COMMENTS:
- initialize() in a6.html initializes the world geometry of four spheres. This function is called in main().
- Only sphere0, the smallest sphere, correspond to the isLight boolean.
- raycast will call raycast2(), and raycast2() will call (the creative component I made) raycast3(). GLSL doesn't allow for recursive funcitons.

- For the CREATIVE COMPONENT, I created the third reflection of the sphere called raycast3().
- localShade doesn't seems to take in value I, so I modified it.
