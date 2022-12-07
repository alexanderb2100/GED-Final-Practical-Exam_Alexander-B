1. Object pooling was implemented in the TA’s starter code by having the enemies in an
object pool where once the last remaining enemy is killed, the one that was killed first
(which returned to the pool) re-spawns. This makes it so that there are constant waves
of enemies that spawn without creating new objects each time, but rather re-using the
same two enemies that are in the object pool. This optimizes the scene because creating
and destroying new enemies each time the player gets a kill would significantly slow
down the game over time. With the implementation of object pooling, it becomes much
more efficient.
2.
