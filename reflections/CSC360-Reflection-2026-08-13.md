# CSC360 Reflection — 13/08/2026

This session moved from the theory of the first two classes into actually building something. We started by looking at the math that underlies computer graphics, including vectors and matrices for transformations like translation, rotation, and scaling, as well as parametric curves and surfaces for modeling smooth shapes. We also discussed how local coordinates eventually get mapped through world space and camera space before finally being projected onto the 2D screen.

We also compared computer graphics with image processing. Graphics starts from abstract mathematical models and parameters and synthesizes a rendered image through shading and rasterization, while image processing starts from existing pixel data and works on filtering, noise reduction, and extracting features from it.

On the security side, we talked about how Git authentication works, comparing HTTPS, which relies on access tokens over TLS, with SSH, which uses asymmetric key pairs for authentication. This tied back into public and private keys, where the public key is shared with GitHub to verify signatures and the private key stays local to sign authentication requests.

The practical part of the session was setting up a JDK and Maven for the first time, and I learned it is generally better to use a slightly older, more stable JDK version rather than the newest release. After that we built our first actual graphic, starting with a simple square. I ran into small issues with sizing and positioning at first, but working through the code helped me understand how changing coordinates controls both size and placement. Overall the session gave a good balance of the underlying math and the freedom to experiment hands on, which made the concepts stick a lot better.
