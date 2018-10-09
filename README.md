# Mari0 FE - Frustrated with a feature's absence? Add it.

git.io/fA7Af


Initial Commit:

region triggers can now detect a specific enemy category - just type a number into the input box. "true" and "false" emulate the vanilla behaviour of enemy detection. this may break other usages of "checkrect".

added givesacoin, givesdecacoin, and givestime for custom enemies. these override givesalife.

also added givestimeamount and givescoinamount.

changed folder to mari0_fe so that things don't crash in unmodded SE.


smb Mappack will no longer disappear if you load anything else.

kooparedflying is fixed - shoutouts to Alesan for this.

scaffolds are no longer invisible in the editor.

Action Blocks are no longer blue.

deleted the map previews of /smb/ so it fit.

---------------

minor text and QoL changes - logic gates are invisible by default, other things that shouldn't change anything

added internal flags --GCP for a modular function that's being worked on, --HAK for a particularly hacky piece of code, --DOC for documentation of what something is supposed to do, --DB for debug, --TODO for obvious reasons and more to come

added globools, globints, and globoolSH(id, func) to game.lua, created globintSH and globintCH, one for setting and the other for checking

added globool functionality to animations

added globint condition and action to animations

added zgbooltrigger and zginttrigger, detectors for global booleans and integers respectively

will soon add outputting to globools/globints to custom enemies

warning: global integers are currently apparently broken
