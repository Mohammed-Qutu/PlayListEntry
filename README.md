# PlayListEntry

## Description
This Java project defines a `PlayListEntry` class that represents a song in a playlist. The class includes attributes for the song title, artist, and play count, and provides mutator (setter) and accessor (getter) methods for each attribute. The project demonstrates the use of encapsulation and basic object-oriented programming concepts.

## Author
Written by Mohammed Qutu.

## Requirements
- Java 21.0.2 or later

## Usage
To use the `PlayListEntry` class, create an instance of the class and use the provided mutator methods to set the song title, artist, and play count. The accessor methods allow you to retrieve and display this information.

### Example Usage
```java
PlayListEntry song = new PlayListEntry();
song.setTitle("Song Title");
song.setArtist("Artist Name");
song.setPlayCount(5);

System.out.println("Title: " + song.getTitle());
System.out.println("Artist: " + song.getArtist());
System.out.println("Play Count: " + song.getPlayCount());
Methods:
setTitle(String title): Sets the title of the song.
setArtist(String artist): Sets the artist of the song.
setPlayCount(int playCount): Sets the play count of the song.
getTitle(): Returns the title of the song.
getArtist(): Returns the artist of the song.
getPlayCount(): Returns the play count of the song.
License
This project is licensed under the MIT License - see the LICENSE file for details.
