We started off by copying the terrain from the main project and bringing it into a new scene for the minigame.
Then we placed 16 floors with colliders on top of the terrain for the player and enemies to stand in.

![image](https://github.com/user-attachments/assets/596ba65c-16f7-4d0f-b79a-4bec7c35b7ed)

Aditionally, we added all the floors into one Empty Object as a parent node.
We also transferred WaveManager and EnemyManager from the project.

![image](https://github.com/user-attachments/assets/7c0c4245-d950-4125-b64a-39181198e01d)

Then we added the walls from a previous created prefab and created a wall on one side of the map, then created an empty
object and called it "wall", then we put all the walls on that object so we can duplicate it four times.

![image](https://github.com/user-attachments/assets/9a48617a-560b-4275-a432-8822cb78d09c)

To create the raindrop, we added a sphere and changed the shape. Then we made a material called rain for the raindrop.
Then we drag it into our assets to make it a prefab.

![image](https://github.com/user-attachments/assets/4570a70e-e94c-498b-9ef9-693eb1c1e82c)

We made this Empty Object called Rain to hold the rain spawners with the "Spawner" script in them,
as well as the raindrop prefab as the spawned object.

![image](https://github.com/user-attachments/assets/a4961cda-c3fc-4da2-bbf1-1dae03fba066)


In order to make everything collide properly, we had to add layers for every component.
Edit > Project Settings > Tags and Layers

![image](https://github.com/user-attachments/assets/c3533574-c4f5-4fb3-ad91-fffd623294d8)

After that, we had to manage the layers that can or cannot affect each other by going to
Edit > Project Settings > Physics, then scrolling down until you see this chart.

![image](https://github.com/user-attachments/assets/2701fb12-5e1d-4d47-ab84-849b5568557d)

Finally, to make our Win and Lose screens, we added an empty object to hold the MinigameMode script
that keeps track of the win conditions and lose conditions.

![{4E547BA5-2255-4594-B18D-799BC2301290}](https://github.com/user-attachments/assets/96617f81-e909-40e1-84cd-ceeeb4806cc2)

For making the win and lose screen, we imported AI-generated images into the assets and turned them into materials.
Then we made two scenes called WinScreen and LoseScreens, and added a Cube on each. Finally, we dragged the materials
into the cubes in the Win and Lose scene respectively.

Win Screen:

![image](https://github.com/user-attachments/assets/6f296f83-1975-4c95-b1f2-0337439313e2)
![image](https://github.com/user-attachments/assets/753d81b5-a6e5-44c4-a1f8-02d274380126)


Lose Screen:

![image](https://github.com/user-attachments/assets/8ba79eae-0719-466d-8701-ab5aa479f8fe)
![image](https://github.com/user-attachments/assets/0d27834a-b6ab-497a-b30b-8105a13e40e5)

