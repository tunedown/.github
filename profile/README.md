## tunedown 🎵 🤠


tunedown is a musical therapy application that takes inputs from a users wearable device (such as a smart watch) and tracks metrics such as heart rate, blood pressure, glucose levels, ecg signals, skin temperature and more. What it does is combines this data with their Spotify playlist data per song. From each song we are extracting properties such as the liveness of the song, the danceability of the song, the energy levels of the song, tempo and more. What we are doing is combining these audio attributes with the users current body attributes and assigning a mood to them based on GPTs LLM. From GPT we gather a mood prompt, and feed this mood prompt over to Suno AI to generate custom real-time songs that modify the audio attributes (tempo, energy..etc.) to help calm the user down and keep their energy levels in line with what their wearables are suggesting.

## Tech Stack:
Python/Flask, JavaSscript/React/Next.js, SQL


## Embedded APIs:
1. [Spotify Audio Features](https://developer.spotify.com/documentation/web-api/reference/get-audio-features)
2. [Spotify Playlists](https://developer.spotify.com/documentation/web-api/reference/get-playlist)
3. [OpenAI API](https://platform.openai.com/docs/overview)
4. [Terra API](https://docs.tryterra.co/reference/using-the-api)

---

### App Demo: [Youtube](https://youtu.be/AN_GnDIGIqY)

### Read more: [Here](https://ballot.hackmit.org/project/spece-xefnr-iyqng-wifdp)
