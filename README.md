Modified LibGDX for my game, focus on extension and small modification to retain ability to merge origin into this branch when new updates/changes are made.

I was growing tired&frustrated of going long ways to work around the framework to extend if for certain things, so this fork is for some of those changes/extension I really need to make that must exist on the lower framework level/layer.

for now modification are explitely applied for Actor class inside https://github.com/libgdx/libgdx/tree/master/gdx/src/com/badlogic/gdx/scenes/scene2d

the rest of modification I tend to just extend in my game repo, and I do not not need to modify anything.

Later on I might make small modifications if there are performance limitation with libGDX regarding 2D/3D, slight modifications, graphics is not something my game will heavilly focus on, I mainly need a very good dynamic UI and this is the reason I will mainly do modification inside the gdx directories, especially for now the scene2d.
