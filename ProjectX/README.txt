A) Class Files

Player.jack
Rival.jack
Bullet.jack
RivalNode.jack
BulletNode.jack
LinkedListBullets.jack
LinkedListRivals.jack
Game.jack
Main.jack
Pair.jack
RandomGenerator.jack
Util.jack

B) Relations between classes

Player contains Pair and RivalNode
Rival contains Pair, Rival, RivalNode and RandomGenerator
Bullet contains Pair and RandomGenerator
RivalNode contains Rival and RivalNode
BulletNode contains Bullet and BulletNode
LinkedListBullets contains BulletNode
LinkedListRivals contains RivalNode
Game contains LinkedListBullets, LinkedListRivals, Player, BulletNode, RivalNode, Pair, Bullet, Rival, RandomGenerator
Main contains nothing
Pair contains nothing
RandomGenerator contains Array
Util contains nothing


C) Instructions to compile

Compile by going to the nand2tetris/tools folder and typing:
./JackCompiler.sh path-to-folder-where-game-is

Running the game
1) Open VMEmulator
2) Load the folder which stores the game
3) Choose "No Animation" option and set speed to fast in VMEmulator
4) Clock Run

