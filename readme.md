# PROJECT FOX GAME

A live pet game in vanillaJS as a part of live workshop by Brian Holt (FEM)

Website Live at https://yashmunjal.github.io/Digital-pet-game

# Rules of the games

  - The game starts in an initialized state. The user must press the center game to get started.
  - Users can switch between the three icons on the bottom using the left and right button. To press one of the icons, they will click the middle button. Users cannot directly click the icons.
  - If they reach the end of the icons and try to go further (click the right button when the right-most icon is selected) it should loop around.
  - When the user starts, the fox will hatch after showing the hatch animation.
  - Once the fox is hatched, show the fox in an idle animation in the day time.
  - The user can switch the weather from day to rain using the weather icon.
  - After some amount of time the fox will become hungry. This should be on some sort of variable schedule to add some unpredictability to the game.
  - The fox can only be fed when hungry.
  - After a fox is a fed, after another random interval, the fox will poop.
  - The fox cannot have the poop cleaned up unless there is poop to be cleaned up
  - When a user cleans up poop, it should add another random interval until the fox is hungry again.
  - The fox cannot be hungry and have pooped at the same time.
  - If the user hasn't fed a hungry fox or clean up a fox's poop after a random interval, it should cause the fox to die and go to the game over screen.
  - After a longer random interval of day/rain, it should become night. It stays night for a fixed interval. The fox does not get hungry, poop, or die in its sleep. Once it wakes up, it starts with a new random interval of hunger and poop. You cannot change the weather, clean up poop or feed a sleeping fox.
  - Once the game hits nighttime, reset the timers. The fox will wake up and the first thing that will happen is it will become hungry.
  - Once a fox dies, the landscape goes into the death scene, the fox becomes the tombstone, and the game is over. If the user presses the middle button again, it restarts the game with a new hatch.



