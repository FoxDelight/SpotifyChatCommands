# SpotifyChatCommands
Chat commands for Spotify control - Song Requests &amp; more
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Spotify Commands</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 700px;
      margin: 40px auto;
      padding: 0 20px;
      background: #f9f9f9;
      color: #222;
    }
    h1 {
      text-align: center;
      color: #1DB954;
      margin-bottom: 1rem;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 40px;
    }
    th, td {
      padding: 12px 15px;
      border: 1px solid #ddd;
    }
    th {
      background: #1DB954;
      color: white;
      text-align: left;
    }
    tr.section-title td {
      background: #d1f3d1;
      font-weight: bold;
      font-size: 1.1rem;
      text-align: left;
      border-top: 2px solid #1DB954;
      border-bottom: 2px solid #1DB954;
    }
    tr:hover:not(.section-title) {
      background: #e0f7e0;
    }
    @media (max-width: 600px) {
      body {
        margin: 20px 10px;
      }
      th, td {
        padding: 10px 8px;
      }
    }
  </style>
</head>
<body>
  <h1>Spotify Commands</h1>
  <table>
    <thead>
      <tr>
        <th>Command Name</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr><td><code>!sr</code></td><td>Request a song (Spotify URI, YouTube link, or artist/title)</td></tr>
      <tr><td><code>!queue</code></td><td>Show upcoming songs (<code>!queue 5</code> = next 5 songs)</td></tr>
      <tr><td><code>!mySongs</code></td><td>Show your requests and estimated wait time</td></tr>
      <tr><td><code>!song</code></td><td>Show the current song</td></tr>
      <tr><td><code>!link</code></td><td>Get the Spotify link of the current song</td></tr>
      <tr><td><code>!last</code></td><td>Show the last played song (<code>!last 3</code> = last 3 songs)</td></tr>
      <tr><td><code>!voteSkip</code></td><td>Vote to skip the current song</td></tr>
      <tr><td><code>!wrongSong</code></td><td>Mark your last request as incorrect</td></tr>

      <tr class="section-title"><td colspan="2">Playback Controls</td></tr>
      <tr><td><code>!play</code></td><td>Resume playback</td></tr>
      <tr><td><code>!pause</code></td><td>Pause playback</td></tr>
      <tr><td><code>!skip</code></td><td>Skip current song</td></tr>
      <tr><td><code>!previous</code></td><td>Play the previous song</td></tr>
      <tr><td><code>!restart</code></td><td>Restart the current song</td></tr>
      <tr><td><code>!volume</code></td><td>Adjust volume (<code>!volume 70</code>, <code>+10</code>, <code>-5</code>)</td></tr>

      <tr class="section-title"><td colspan="2">Playlist Commands</td></tr>
      <tr><td><code>!playlists</code></td><td>List your playlists (<code>!playlists 2</code> to select one)</td></tr>
      <tr><td><code>!playPlaylist</code></td><td>Play the selected playlist</td></tr>
      <tr><td><code>!addSong</code></td><td>Add the current song to the selected playlist</td></tr>

      <tr class="section-title"><td colspan="2">Block List</td></tr>
      <tr><td><code>!blockSong</code></td><td>Block the current song or block by name/URI</td></tr>
      <tr><td><code>!unblockSong</code></td><td>View or unblock songs from your blocklist</td></tr>

      <tr class="section-title"><td colspan="2">Other</td></tr>
      <tr><td><code>!spotifyCommands</code></td><td>Show this command list in chat</td></tr>
    </tbody>
  </table>
</body>
</html>
