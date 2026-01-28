# CS260 - Music Review Application

### Elevator pitch

Movies, TV shows, games, all of them have many websites dedicated to rating and keeping track of experienced media. However, music has no such mainstream equivalent. Rather than the limited information coveyed by just sharing playlists, the application with allow users to display all time favourite artists and songs and currently listening music, catalog and write reviews on listened music which they may not want to have on personal playlists, and view ratings by other users. This allows more flexibility and expression in users' ability to share and find new music. 

### Design

Potential Profile UI
![Mock](sample-images/SampleProfileUI.png)

Potential Library UI
![Mock](sample-images/SampleLibraryUI.png)

Potential Song Page UI
![Mock](sample-images/SamplePageUI.png)

### Key features

- Secure login over HTTPS
- Personalize profiles to display favourite and currently listening to music
- Catalog and keep track of listened to music
- Rate and write reviews on songs and albums
- View most highly rated music by other users
- Filters to narrow down search results
- Custom tags to organize music collection
- Possible future implementations:
    - Comment on specific highlighted parts of a song or lyrics
    - Play previews of music or selected favourite parts
    - Filter ratings by self assigned tags to see how both lovers and outsiders view an artist or song
    - Recommend similar artists or songs
    - Deeper analysis to music tastes and preferences

### Technologies

I am going to use the required technologies in the following ways:

- **HTML** - Uses correct HTML structure for application. 6 different views: One for displaying songs, albums, and artists, user profile, one for user's catalog and ratings, and one for overall rankings
- **CSS** - Application styling that looks good on different screen sizes, displays artist art and album covers.
- **React** - Provides login, customizing profile, displaying other users' profiles, applying ratings and listened status, displaying updated rankings
- **Service** - Backend service with endpoints for:
  - login
  - retrieving user and other user's ratings
  - retrieving artist, album, and song metadata by calling from a third party API
- **DB/Login** - Store users, ratings, profile customizations in database. Register and login users. Credentials securely stored in database. Can't customize profile or give ratings unless authenticated.
- **WebSocket** - As ratings are given, live updates to overall ratings

## HTML deliverable
For this deliverable I built out the structure of my application using HTML.

- [x] I completed the prerequisites for this deliverable (Simon deployed, GitHub link, Git commits)
- [ ] **HTML pages** - 
- [ ] **Proper HTML element usage** - 
- [ ] **Links** - 
- [ ] **Text** - 
- [ ] **3rd party API placeholder** - 
- [ ] **Images** - 
- [ ] **DB/Login** - 
- [ ] **WebSocket** - 