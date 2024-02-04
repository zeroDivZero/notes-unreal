# KEYBOARD

Pressing or releasing keyboard key. When adding, search for desired key under **Keyboard Events**.

![Keyboard Event](/assets/Blueprint/blueprint-event-keyboard.png)

When running game in window mode, be sure to click in window first to make it active to receive keyboard events.

If not working, try connecting event **BeginPlay** to node **Enable Input**. Or, under **Class Defaults &rarr; Input &rarr; Auto Receive Input**, change value from **Disabled** to **Player 0**.
