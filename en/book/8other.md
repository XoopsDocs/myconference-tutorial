# 8.0 Info for Developers

Events (date / day)
- Shipping talks by visitors to the site?
- Sponsors / Organizer?
 - Ask if they are ordered by alphabetical order
 - Categories of sponsors (tick if put in the footer)

#### Blocks:
- Tracks
- Program

#### Features:
- Registration
    - "fast" print of the entry form
    - external registration
    - Form creation by users (FormBuilder?)
    - Registration -Statistics
- Automatic creation of the program grid
- Detection of inconcistencies, overlaps
- Press Room?
- Comments from people on the talks?
- Notification of changes?
- PDF with the program (sponsors and organizer)


## Database 

####Tables:

- conference_congress 
- conference_speakers 
- conference_speech_type 
- conference_speech 
- conference_tracks 
- conference_sponsors 
- conference_speech_eval

####Fields in Tables:

+ conference_congress 
    - conid 
    - sdate 
    - edate 
    - title 
    - subtitle 
    - subsubtitle 
    - logo
 

+ conference_speakers 
    - speakerid 
    - name 
    - email 
    - descrip 
    - photo 
    - url