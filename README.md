# MusescorePedalingFix
Fixes the piano pedal being "stuck" when trying to run a MuseScore generated midi in various commercial Piano VSTs.

# Requirements
- Python3 https://www.python.org/
- Mido https://pypi.org/project/mido/

# Installation

1. Clone this GitHub project.
2. Open a terminal, for example Powershell.
3. `pip3 install mido`

# Usage
usage: `python3 pedalfix.py <file>`
  
# Example
`python3 pedalfix.py test.midi`

Outputs: `pf_test.midi`

# Verifying
Try running the generated "pf_" midi file in a vst such as Garritan CFX. The pedaling should now work as it did in MuseScore.
