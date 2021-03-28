## Description

Getting the demos to run took a bit of work. As I did with project one, I used (https://lazyfoo.net/tutorials/SDL/01_hello_SDL/windows/msvc2019/index.php) as a reference to get SDL properly set up in the Visual Studio project. From there, I did have an issue with the glm folder. I ended up adding the folder path to "Include Directories" under project properties. After this, the demos ran smoothly.

The first three questions for section B were pretty straight forward. The changes for Q1 and Q2 were visible, and intuitive enough to understand. Q3 was extremely similar to a feature I had implemented for project 1, so that went well. Q4 took me a little bit, just in terms of figuring out how the vertices were being read from the file. 

## Compile and Run the Demos

**TriangleColored.cpp**

![colored_tri](https://user-images.githubusercontent.com/59031606/112705193-aa048580-8e6b-11eb-8766-b53806419278.png)

**Cube.cpp**

![cube](https://user-images.githubusercontent.com/59031606/112705148-7c1f4100-8e6b-11eb-8626-e9d4855715aa.png)

**CubeLit.cpp**

![lit_cube1](https://user-images.githubusercontent.com/59031606/112705236-d6200680-8e6b-11eb-8382-89e0df7e6c35.png)

![lit_cube2](https://user-images.githubusercontent.com/59031606/112705250-e3d58c00-8e6b-11eb-9230-5a32b6e2b83f.png)

**ModelLoad.cpp**

![teapot](https://user-images.githubusercontent.com/59031606/112705592-9bb76900-8e6d-11eb-9c37-d31734055fb5.png)


## Quick Checks Questions

### Q1

Changing these parameters changes where the "My OpenGL Program" window opens. For example, putting zero for the second and third parameter makes the window appear at the very top left of the desktop.

### Q2

The resulting image after removing this call is a cube that you can kinda see the inside of? Not see-through, but you see through the side(s) that should be facing you.

![image](https://user-images.githubusercontent.com/59031606/112741300-29688680-8f4a-11eb-9835-9f4dc0a33530.png)

### Q3

The only thing I needed to change for this was to add another if statement in the event loop, checking if the 'q' key was let up. If it was, the quit variable was set to true;

### Q4

![image](https://user-images.githubusercontent.com/59031606/112765276-0bdeff80-8fd2-11eb-8b51-d0d628610ced.png)
