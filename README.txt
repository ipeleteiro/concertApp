This is an app that will (hopefully) do as follows when complete: 
    - notify users of their followed artists' concerts in a regular time frame

Other possible features include:
    - using Spotify API to get top artists and reccomend accordingly
    - set location and notify accordingly

This is the current plan for the full stack web app:
    - Frontend: UI for users to:
        - agree to access Spotify user data
        - set specific artists to follow + locations
        - Using: React
    - Backend: figuring out when artists are on tour using API (Spotify, Ticketmaster, or Bandsintown)
    - Database: storing user data using Firebase(?)
    - Notifications: by email using Gmail SMTP (or other)
    - Automate: checking for updates periodically (celery in Pyhton)
    - Host: AWS probably best
    