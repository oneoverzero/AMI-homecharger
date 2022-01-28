# AMI-homecharger
Fancy and complicated way to charge a Citröen AMI


Motivation:
  Citröen AMI only charges though a simple Schuko plug into European 230V wall socket. Using a mechanical timer or a smart plug, as only the phase is disconnected, doesn't work. Perhaps a test of the quality of the earth connection must be made simultaneously with the connection of the phase?

Since we're assuming there is active Live + Neutral + Earth detection, additional hardware is needed, hence this project is born.

It uses a Shelly module to connect/disconnect the phase line, and uses a 2P contactor to simultaneously connect/disconnect the neutral and earth lines reaching the socket.

Two lights have been added, one to show the EVSE is connected to the mains, and another to indicate the charging circuit is activated. A button allows to switch on/off manually, instead of using the scheduling or remote control of the Shelly module.
