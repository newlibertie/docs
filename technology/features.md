
#UI

## App
  - Capture video and stream it to back-end service
  - Play back video
  - Allows you to become witness
  - Bluetooth scan
  - Digital signature on content chunked in 1 min intervals
  - Authentication/Account (reuse jfi)
  - Gesture/voice recognition

## Web UI
  - Play back video
  - ACR
  - Authentication/Account (reuse jfi)



# Backend

### Auto prefilter for low quality
 - Tech?

### Video Storage
 - Tech? (Replicated)
 - Video is encrypted
 - Commitment to Block-chain

### Workflow engine
 - Social farm
 - View - likelihood of cluster of recording is crime scene (reuse icebraker nbd)
 - Call voting

### CouchDB
 - Authentication (see UI)

### Voting Service
  - TBD
    - merge all branches and set up unit and integration tests
    - deploy

### Video processing
  - Steganography: modify the o/p slightly
    - encode information
      - place and device of playing video?
      - time of playing
      - link of video
      - place of recording
      - video recording time [start, end]
  - objectionable content videos
    - Reject video storage acceptance
    - Flag accepted videos through review process
  - Redacting: Allow plugable video/audeo filters
    - a list of filters is available to be applied to playing of a video
      - Hiding identity/face of the subjects
      - Modulating voice of the subjects
  - Restrict video playing availability
    - by geographical location of video player
    - by age of the requesting user
 
### Video Tools
  - A tool to read and interpret the Steganograph in the playing video
    - Determine the integrity of the video
      - Any tampering done
      - filters used
    - Identify the context of an excerpt video clip
      - link of the RaviReporter video
      - which subsection of the RaviReporter video is that clip

### Video voting
  - Voting anonyously on videos for various polls
    - By the judges on 
      - Crime happened
      - Type of crime
      - Seriousness of the crime
      - whether the accompanying description of the crime is an accurate one
      - If the redacted video provides sufficient context etc 
    - By various groups of viewers
      - polls organised by various organizations or individuals
      - polls for features and enhancements in the product organised by the developers

### APK (binary format for android application package)
  - Build the APK
    - Android (has a secret key. How to protect it?)
    - There will be a bundle of secrets, Computation on these secrets yeilds a private key
    - One of the component of the secrets will be missing
    - When app comes live, web service will provide the missing piece, on verification to the app. {How to allow app to run a dynamic code given by the server?}
    - 
