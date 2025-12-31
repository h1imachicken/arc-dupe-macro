ARC Raiders Snitch Scanner Duplication Macro
A simple macro/tool for duplicating Snitch Scanners in ARC Raiders using a network lag simulation technique (disconnect/reconnect timing to interrupt the throw action).
How It Works
This exploits a desync glitch by briefly simulating network issues during the throw animation, causing the server to register the animation but not the item drop—resulting in a duplicate spawning on the ground.
Setup & Usage

Equip the Snitch Scanner in your hand.
Go in-game to a safe area (or test in practice area).
Press the trigger key (default: F3) to run the macro.

Tuning the Timings
You'll need to adjust the Network Start Delay and Network Offline Time for your system and connection:

Recommended starting values: Start Delay = 0.75s, Offline Time = 2.5s
These work well for many, but vary by PC specs, ping, and WiFi stability.

Testing Process:

Run the macro a few times.
If the Snitch Scanner fully drops to the floor (and you lose it), timings are too off—reduce offline time or increase delay.
Goal: It should only play the throw animation without actually dropping the item.
Once that's consistent, fine-tune slightly until duplicates appear (two Scanners spawn on the floor).
Success rate is ~90% with perfect timings—always test 2-3 runs per adjustment, as results can vary slightly.
