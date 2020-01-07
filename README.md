# MusescorePedalingFix
Fixes the piano pedal being "stuck" when trying to run a MuseScore generated midi in various commercial Piano VSTs.

# Requirements (Install)
- Python3 https://www.python.org/
- Mido https://pypi.org/project/mido/

# Setup
1. Install Python 3
2. Clone this GitHub project.
3. Open a terminal, for example Powershell, in the directory of the cloned project.
4. Run `pip3 install mido` in your terminal.

# Usage
usage: `python3 pedalfix.py <file>`
  
# Example
`python3 pedalfix.py test.midi`

Outputs: `pf_test.midi`

# Verifying
Try running the generated "pf_" midi file in a vst such as Garritan CFX. The pedaling should now work as it did in MuseScore.
