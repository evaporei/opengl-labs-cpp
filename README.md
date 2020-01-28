# OpenGL Labs

This is yet another pet project of mine to play around and do something cool with OpenGL and C.  
Check out the Up and Running section to get it started

## Tech Stack
- C
- Glew, Glfw, Glm

## Up and Running 

**macOS:**
```
$ brew install glfw glew glm 
```

Also you will have to change the `working directory` in `Xcode`, like this:

- First go to `Product` > `Scheme` > `Edit Scheme...`

<img width="940" alt="how-to-find-product-edit-scheme" src="https://user-images.githubusercontent.com/15306309/72669950-9e6f3080-3a16-11ea-8dfd-22f98b6a8722.png">

- Then go to `Options` and change the `Working Directory` to a folder like this:

```
/where/youve/cloned/opengl-labs-cpp/opengl-labs-cpp
```

Which is where the project code is (`.h`, `.hpp` and `cpp` files).

<img width="897" alt="how-to-edit-working-directory" src="https://user-images.githubusercontent.com/15306309/72669951-9e6f3080-3a16-11ea-83dd-da116b5cdb06.png">

**Linux | Windows**
```
g++ application.cpp objloader.cpp shader.cpp stb_image.cpp -o opengl-labs-cpp -L/usr/X11R6/lib/ -lGL -lGLU -lglut -lGLEW -lglfw -lGL -lX11 -lXi -lXrandr -lXxf86vm -lXinerama -lXcursor -lrt -lm -pthread
```
