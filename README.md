Last.fm Playlists
==================

This is a coding project for the Nashville Software School. The goal is to create a site that allows the user to enter multiple artists and then see a list of the most listened to tracks from those artists using Last.fm's API.

The app can be viewed live at:<br />
https://lfmplaylists-yr773.backliftapp.com/

The site has the following specs/features:

Phase 1:<br />

<ul>
  <li>uses the Bootstrap framework</li>
  <li>collects the following information from the user:
    <ul>
      <li>artist name</li>
    </ul>
  </li>
  <li>communicates with last.fm's api to find that artist's bio and most played tracks</li>
  <li>saves artist information to the server using Ajax and JSON</li>
    <ul>
      <li>artist name</li>
      <li>track name of top tracks</li>
      <li>number of plays for each track</li>
    </ul>
  </li>
  <li>display artist bio</li>
  <li>display track details in an ordered listing</li>
</ul>

Phase 2:<br />

<ul>
  <li>allow a user to enter another artist</li>
  <li>get top tracks details from last.fm</li>
    <ul>
      <li>track name of top tracks</li>
      <li>number of plays for each track</li>
    </ul>
  <li>creat an ordered list made up of tracks from both artists</li>
</ul>