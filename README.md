# piAutomower2xx
Override control for Husqvarna Automower with a Raspberry Pi. 
Primary goal of project is to install a Raspberry Pi inside the mower to manually control the wheel motors by wifi. 
Secondary goal, adding movement sensors to steer away from wife or towards cat (relax, cutter motor off in the second case) .







Todo\:
- [x] Make a Serial control cable (TTL 3.3V)
      (https://forum.arduino.cc/t/controlling-automower/226731)
- [x] Spoof movment command sets from Tweak Automower by Poildecarotte
- [x] Make a basic commandline python script
- [x] Install Raspberry with neccesary mods for DC power ( partly done )
      Ok lost track a bit here and mouted a pair of foam cannons and a Darth Vader clock modified to webcam.
      Made a GUI but never got around to automate it for chasing the cat.
- [ ] Modify mower to be able to control it with lid closed ( disable lid switch from raspberry gpio )
- [ ] Figure out how to control wheel speed ( partly done )
- [ ] Finish basic README
- [ ] Figure out how to design the command set for future implementation in other projects.
- [ ] Initial upload

List of status replies at https://github.com/nchorherr/openhab2-binding-husqvarnaam/tree/master


