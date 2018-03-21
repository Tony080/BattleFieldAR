# Battle Field AR v0.1

This is an Augmented Reality(AR) First Person Shot(FPS) game for Android devices.

## Tools used
TensorFlow for Android<br>
Google Firebase



## Descriptions:
This game is built on the [demo of TensorFlow for Android](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android). 
It's using YOLO neural network to do the object detection. Then replace the object box with monsters as the same size of the box.<br>
A player can hit on the anywhere of the screen to shoot. If the monster is in the center of the screen, there will be a longer vibration(50ms). 
If the shot is missed, there will be a shorter vibration(20ms).<br>
The game lasts for 30 seconds for a round. And it will upload your score to Firebase and display the leader board as the result.
<br><br>
Notice that, this game is still under development. For now, it's only a project done within a quarter of my university. <br>
There are still a lots of jobs to do:
1. Implement object tracking
2. Assign a health point for each monster
3. More kinds of monsters
4. More kinds of firearms
6. A shop utilities on the Google Cloud Platform
7. Sounds effects

## Build the game
To build the game you need to download [bazel](https://bazel.build/).<br>
Then, see [README.md](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/android/README.md)
for more details.
