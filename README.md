# game-task4-round-world

The game has 2 main objects:
 
   1. player- has collider and rigidbody. Player also has a scripts that made him move, killed when it hit enemy, and shoot laser.
      https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/1-movers/KeyboardMover.cs
      
      https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/3-collisions/DestroyOnTrigger2D.cs
      
      https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/2-spawners/LaserShooter.cs
      
   
   2. enemySpawner- a prefab that spawn the enemies.
     https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Prefabs/EnemySpawner.prefab


We addded a script for the player that when the player cross the screen it comes back from the other side.

https://github.com/Noa-Amit/game-task4-round-world/blob/main/Assets/Scripts/3-collisions/TransportObjectOnScreenExit.cs

