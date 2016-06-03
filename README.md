# ShotCat
A lightweight database tool for film and television post-production.

# History
Many film and television productions hack together a database for footage tracking. Methods are varied and rely on software that could be deprecated virtually overnight. Scripted features and television shows often use custom Filemaker templates; in my time in unscripted reality television post-production, I've seen bad implementations of cloud storage or, even worse, an FTP server (ack) for notes, logs, transcripts, and so on, with no way to search across them without third-party tools. I'd like to fix that and offer an easy to use, flexible cataloging system.

# Roadmap
I plan to make this an open source, lightweight alternative to these sort of messy solutions. I'm not a professional
coder by trade, so this will be a learning process. There are no promises and no guarantees of delivery; features will
be added at my leisure. Nyeh nyeh.

# Anticipated Features
* _Shot database_: tables with metadata, comments, and timecode. Ideally this would interface/export as an ALE so that it could be applied to clips in Avid, but that's secondary to a good search tool.
* _Logs_: a location to store logs/transcripts/notes, so that they could be searched as quickly as a shot database.
* _Universal search_: looking for a phrase? Looking for someone doing something you remember seeing? If it's logged and tagged properly, you'd call up both the shot info _and_ the relevant log/transcript.
