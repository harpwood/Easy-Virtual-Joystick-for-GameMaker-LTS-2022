# Easy Virtual Joystick 
## for GameMaker LTS 2022
Introducing the Easy Virtual Joystick for GameMaker LTS 2022! This versatile and intuitive joystick is the perfect addition to your GameMaker toolkit. With customizable settings and easy integration, it's the one and only virtual joystick that you'll ever need, guaranteed. Whether you're making a platformer, action game, or any other type of mobile game that requires smooth and responsive joystick controls, the Easy Virtual Joystick has got you covered. And at an affordable price, it's a no-brainer for any serious game developer. So why wait? Download the Easy Virtual Joystick for GameMaker LTS 2022 now and take your game to the next level!

Integrating the Easy Virtual Joystick into your GameMaker project is a breeze. With just a few lines of code, you can create a virtual joystick controller object and use it to control your game. Here's an example:

```gml
// virtual joystick controller object
// Create event
vj_left = new virtual_joystick();

// Step event
vj_left.step();

// Draw GUI event
vj_left.draw_gui();

// Clean up
delete vj_left;
```

But don't let its simplicity fool you! The Easy Virtual Joystick is a robust and versatile tool that offers a wide range of options for customizing both its behavior and appearance.

Let's see a very brief overview of the virtual_joystick constructor and how it works. 

```gml
/**
 * Creates a new virtual joystick with the specified configuration, skin and position.
 *
 * @constructor
 * @param {number} _x - The x-coordinate position of the joystick on the GUI layer.
 * @param {number} _y - The y-coordinate position of the joystick on the GUI layer.
 * @param {struct} configuration - The configuration object for the joystick (see example structs above).
 * @param {struct} skin - The skin object for the joystick (see example structs above).
 */
function virtual_joystick(_x = undefined, _y = undefined, configuration = undefined, _skin = undefined) constructor {
```

 The Easy Virtual Joystick offers flexibility in placing the virtual joystick, with the default position being at the bottom left of the screen. You can further fine-tune the joystick's behavior with the configuration struct and customize its appearance with the skin struct. The joystick comes in two modes: FIXED position and INVOKABLE. The INVOKABLE mode can be configured to be visible on the screen only when touched or remain at the last touch position within a predefined area.

You can find a complete documentation in the Easy Virtual Joystick in the [wiki](https://github.com/harpwood/Easy-Virtual-Joystick-for-GameMaker-LTS-2022/wiki).
