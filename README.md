# Arduino Braccio Control with Keyboard
This project allows you to control the Arduino Braccio robotic arm using keyboard inputs.

## Project Structure
my_keyboard: Contains the main code for controlling the Arduino Braccio with a keyboard. 

### Keyboard Command Usage

#### Motor Selection
First, choose the motor you want to control by entering a number between 1 and 6. Each number corresponds to a specific motor on the Braccio.

#### Motor Movement
Press and submit the letter 'a' to decrease the motor's angle.
Press and submit the letter 's' to increase the motor's angle.
The motor will move by a predefined step size with each input.

## Important Note
It is recommended to use the provided library functions instead of directly sending native commands. The Braccio arm is not designed to handle rapid movements in a single direction for any motor. Using library commands ensures smoother and safer operation of the robotic arm.

