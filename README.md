# SpotifyAPI-Java
[Unmaintained]
A rushy built Spotify API wrapper for Java

Intro
========
Spotify API wrapper for Java. Written as part of a university project.  
Really simple to use.  

Requirements
=================
Requires a Spotify API Client ID and Client Secret

Demo
======

```
  String id = "e306c20a95844942b5ec74fcd724c739";
  String secret = "8f91376b008e411282d6c5dd550817e7";
  String songID = "3YKptz29AsOlm7WAVnztBh";
  
  SpotifyAPI spotify = new SpotifyAPI(id, secret);
  String results = spotify.getAudioAnalysis(songID);
  System.out.println(results);
```

TODO
======
Fix and Generate Documentation
