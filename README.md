# Analog-Computer-Symbols
Analog Computer Symbols library for KiCad 6.x and 7.x


  I designed a symbol library of analog computer symbols for drawing analog computer schematics in KiCad (6.x). \
  It's still working 0K after updating KiCad to version 7.x. \
  (It’s only for drawing the schematics.)

  ‘**Analog_Computer_Symbols.kicad_sym**’ is the KiCad library file. (It's compressed into a zip-file.)

  This is how I installed it **on my Mac**. 
  *   If not done already first download and install the latest KiCad 7.x. (or 6.x) \
      (All KiCad downloads can be found here: https://www.kicad.org/download/ )
  *   Run KiCad. \
      This will create a ‘KiCad’ directory in the ‘~/Documents’ directory.
  *   Look for directory: ‘~/Documents/KiCad/6.0/symbols’
  *   Copy ‘Analog_Computer_Symbols.kicad_sym’ into the ‘symbols’ directory.
  *   You’re probably still running KiCad. \
      Open via KiCad-menu: Preferences -> Manage Symbol Libraries…
  *   There are some buttons almost on the bottom of the ‘Symbol Libraries’ window. \
      The second one is the one with a ‘map’ symbol. \
      Click that button with hint: ’Add existing library to table’
  *   Now add file ‘Analog_Computer_Symbols.kicad_sym’

  The current version of the Analog Computer Symbols library has too much symbols for a THAT user. \
  But it probably misses some symbols for a system like the “Analog Paradigm Model-1”. \
  This library is work in progress ;-) \
  And do let me know if something is missing or wrong.

  KiCad already has symbols for resistors, capacitors, (zener) diodes and misc. I/O connectors. \
  These are not added to the library.

  Here a list of the current symbols:
  *   Cartesian to polar conversion
  *   Coefficient potentiometer with 2 terminals
  *   Coefficient potentiometer with 3 terminals
  *   Comparator (relay version with switch down)
  *   Comparator (relay version with switch up)
  *   A divider function; ‘numerator’ and ‘denominator’ can be placed into the divider symbol
  *   General function symbol with one input
  *   General function symbol with two inputs
  *   General function symbol with three inputs
  *   General function symbol with two inputs, incl. ‘x’ and ‘y’ labels
  *   General function symbol with three inputs, incl. ‘x’, ’y’ and ‘z’ labels
  *   General function symbol with two inputs and two outputs
  *   Integrator with one up to six inputs
  *   Integrator with one up to six inputs and a initial condition pin
  *   Inverter, there are separate ‘+’ and ‘-‘ symbols that can be placed into the inverter symbol
  *   Two pole multiplier with ‘X’  symbol, either with or without a leading ‘+’ or ‘-‘
  *   Two pole multiplier with ‘∏’  symbol, either with or without a leading ‘+’ or ‘-‘
  *   Two pole multiplier with a big ‘X’
  *   Four pole multiplier with ‘X’ symbol
  *   Four pole multiplier with ‘∏’ symbol
  *   Open amplifier with one up to six inputs
  *   Two different ‘pin’ or connector symbols
  *   Polar to cartesian conversion
  *   A square function
  *   A square root function
  *   Summers with two up to six inputs

  Some text symbols:
  *   ‘denominator’
  *   ‘numerator’
  *   ‘IC’ for initial condition
  *   Three versions of ‘SJ’ for summing junction
  *   ‘-1’
  *   Two versions of ‘1’ 
  *   ‘+1’
  *   Five versions of ’10’

  By my interpretation… 
    as example and test an “Integrator / Sample & Hold” symbol with one input. \
    In the KiCad symbol editor this symbol is called “Integrator_SH_1”.

  **Enjoy** the library and **HAPPY Analog Computing!**, \
  Arno.
  
