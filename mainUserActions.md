# main user actions
    * On start of Ravi Reporter app (iOS|Android|Browser), if user's credential are absent or expired, obtain credentials (password/...) to login to the backend service. Phone number (public id) is obtained from the device or explicitly obtain it from the user.
    * Select the landing page (Recording|Playing)
    * Select account profile setting
        * Select video storage plan (free|paid tiers)
        * Setting a payment method|making a payment
        * Setting standby video recording buffer size|time
    * In Recording page
        * Start recording an anonymous(public) video
            * In stealth mode
            * In non-stealth mode
        * Start standby recording mode
        * While in standby recording mode
            * Cancel standby mode
            * Hand-gesture|voice-command to start recording (private) video
        * Start recording private video
        * While video is being recorded
            * Cancel video recording?
            * Stop recording private|anonymous (non-stealth mode) video. 
            * Hand-gesture|voice-command to stop recording private video
            * Q:What would be a safe way to stop recording stealth-mode anonymous video?
    * In query page, list top 'n' videos under some standard pre-canned queries for anonymous and private videos
        * Refresh video lists
        * Select a video 
            * Play selected video
            * Delete selected video
            * Claim ownership of selected unclaimed anonymous video
            * Share selected private video
                * find, list and select users to share select private video
        * scroll up|down a video|user list
        * Vote up|down a playing anonymous(public) video for various polls
        * Comment on playing video
