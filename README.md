# sony-cn910-breakout

Repository for schematics and PCBs for using Sony Camcorders with the VC-195 board and CN910 FPC service port.

The full version is for connecting to the service ports (CN910) of my sony handycams and 1. amplifying the FM RF signal for `vhs-decode` and 2. using a raspberry pi to interface with the camcorder via LANC.

The simplified version is simply meant to give me the ability to connect to the camcorder's FM RF output for external amplification. Only the `PB RF`, `REC RF`, and `REG GND` pins of CN910 are available for connection via SMA jack. A few other CN910 signals have test points, but the FM RF signals are the only ones with an SMA connection.
