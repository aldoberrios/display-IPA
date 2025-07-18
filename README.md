# Display the IPA chart in a character-based terminal
The idea is to create a bash file that can be used to display the IPA chart in a text based format in a linux terminal, such as the Gnome terminal.

# Already done
- [x] Other symbols
- [x] Suprasegmentals
- [x] Diacritics
- [x] Tones and word accents

# For future development
- [ ]  Add options to zoom in to a particular area of the chart
- [ ]  Add an option to visualise Unicodes of the respectice symbols

# How to Use IPA chart

1. Move the script to your local bin

<code>   mkdir -p ~/.local/bin
   cp IPAchart.sh ~/.local/bin/
   chmod +x ~/.local/bin/IPAchart.sh</code>

2. (Optional) Add an alias for easier use

Open your .bashrc:

<code>   nano ~/.bashrc</code>

Add this line at the bottom:

<code>   alias IPAchart="IPAchart.sh"</code>

Save and close, then reload:

<code>   source ~/.bashrc</code>

3. Now just type:

<code>   IPAchart</code>