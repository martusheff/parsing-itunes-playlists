# parsing-itunes-playlists
 Exporting the XML representation of iTunes playlists and visualizing the data with set parameters.

- use existing (or add your own) iTunes XML exports to '/test-data' folder
- open terminal, navigate to location of 'playlist.py'
- run one of the following commands (where 'filename' is your file name):
  python3 playlist.py --common test-data/filename.xml test-data/filename.xml
  python3 playlist.py --stats test-data/filename.xml
  python3 playlist.py --dup test-data/filename.xml
