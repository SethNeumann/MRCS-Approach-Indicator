# REPO NAME: EagleTemplate-new
## License: Creative Commons Attribution-NonCommercial-ShareAlike

The approach indicator supports up to 4 stations, each with 2 sensors on each side (that is an East home, East distant and West Home West distant).  THese are optical
sensors connected to analog inputs of the Arduino Nano.  By checking the sequence in which the sensors are covered the sketch (by Jon Schmidt) sets a directional stick
and only fires it's output (relay contact closure) on inbound trains.  The Arduino monitors ambient light and continuously re-calibrates.  An additional two stations are
provided with digital inputs, the user supplies complete detector units such as the MRCS EOPD or EOPDx4 for train detection.
