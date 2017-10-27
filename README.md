# unreal-blueprint-1
Unreal Engine Tutorial (Intro to Programming)
Blueprints Basic Logic: If you want a character to jump at the point of contact (collision) the blueprint logic would go something like this: ON_COLLISION > IF_PLAYER > true > APPLY_FORCE, ELSE > DO_SOMETHING_ELSE

The Empty Actor Asset is the most basic function of the program, an artefact that can stand-in for anything else required in the game. When dragging an Empty Actor to the stage, you first drag the Empty Actor to the stage, then apply the Cube or Sphere shape. Using the WER keys for move, rotate, and scale (like Maya) you can adjust the Empty Actor as required. The Actor receives the Component. In Unity the actor is a game object.

When creating a blueprint: click on the actor, open the Select Path Window, then add blueprint from the dropdown menu. The blueprint will be created in the tray below.

Linking between actors and commands in blueprints requires the event graph and connecting all listeners so that the individual components and actors to which they are attached, work in unison through the logic network.

When it comes to blueprints, always follow the white line. It tells the story of the action. The other frame windows are for support structures built around the main story (white line). Also consider the timeline, which essentially roves the actions created within blueprints over time. Always follow the white line to chart the progress of any action, then consider the time over which the action will occur - in this case the door that opens (ie the action) and the time over which the door opens.
