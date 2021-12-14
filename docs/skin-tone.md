# [⌂](./README.md) Skin Tone

John Henry Thompson
2021

SKIN TONE is a two-screen experience:

# Screen Right:

On the right screen, a live video feed of the participant’s face is sampled and processed using a
[Machine Learning library that lets you tap into an algorithm](https://learn.ml5js.org/#/reference/facemesh)
which identifies faces and categorizes them in a certain way. It was very curious to me that the algorithm took any face and reduced it to 400+ points. I took those points and created the triangular “mesh” using an algorithm called “Delaunay” named after Boris Delaunay, a Russian mathematician, but also evoking Cubist artists Robert and Sonia Delaunay. The Delaunay algorithm converts any series of points into a mesh of triangles. The machine learning algorithm is capable of identifying multiple faces in any circumstance. I am tapping into one face at a time and doing an algorithmic summary of the face. I take this algorithmic summary of the face, I create this triangular mesh to represent the face and then using what the algorithm tells me is the face I create an approximation of the skin tone.

# Screen Left: Mosaic

This screen shows stills from the 8 most recent participants in the project creating a border around the center which is the live skin tone mesh seen on the right screen.

SKIN TONE is very rich not just across people but within one person. The most dramatic variation within one individual is the contrast between the back of the hand and the palm in brown skinned people. SKIN TONE is about using the algorithm to extract what is an approximation of our skin tone. This project interrogates what we celebrate about our textures.

SKIN TONE is inspired by the work of
[Brazilian artist Angelica Dass’ Humane project](https://angelicadass.com/photography/humanae/)
“...attempting to document humanity’s true colors rather than the untrue labels “white”, “red”, “black” and “yellow” associated with race.” Using artificial intelligence and live video effects SKIN TONE interrogates our tendency to reduce very complex phenomena into something singular and invites us to reflect on this drive for efficiency and uniformity.
