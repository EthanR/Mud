## Mud

- Text based (but also graphic capable) game with different rooms, dungeons, puzzles, items, basically role playing. 
- Commands based - have to discover all commands
- Potentially distributed as an open sourced executable
- Open sourced server for locals and customs
- Command engine
- Rules engine
- Multiplayer
- Quests and raids including matching
- Community market
- Networking
- Localization

<pre><code class='language-cs'>const string MUDGREETING = "Hello Player and welcome to the Mud.";
const string PRIVATEEXPANSEGREETING = "You are in your private expanse. There is a bright light constantly within reach.";
const string HELP = "HELP";
const string HELPHELPTEXT = "HELP\tThe HELP command prints your known commands and usage details. Type HELP [COMMAND] to get details for a specific command.";
const string HELLO = "HELLO";
const string HELLOHELPTEXT = "HELLO\tThe HELLO command allows you to enter your private expanse.";
const string DISCONNECT = "DISCONNECT";
const string DISCONNECTHELPTEXT = "DISCONNECT\tThe DISCONNECT command disconnects from the game.";
const string ALIAS = "ALIAS";
const string ALIASHELPTEXT = "ALIAS\tThe ALIAS command allows you to create an alias for a given command. Type ALIAS [EXISTING COMMAND] [NEW COMMAND NAME].";
</code></pre>



- // Effect that causes your player to forget lose known commands AMNESIA
- // NAME CHANGE - change your own name
  - // Pronouns
  - // Profession
  - // Race
  - // Age
- // Ability to create your own commands, your own player properties, your own world building, change game rule engine
- // EXTENSION/ADDON/PLUGIN command to enable extensions - also community open source driven
- // Enable/unlock graphics
- // Enable/unlock audio
- // Inventory collect items
- // Mini games 
- // Streamer mode
- // Save game
- // Scripts - highly configurable but can also be used to quickly rediscover or preconfigure known commands kind of like a Docker file. - Community shared open sourced scripts, allows for different pre-built configs almost analogous to different shells like zsh
- // Unlock multiplayer world
- // Travel to other locations
