
# All M3U Tags For IPTV Playlist

The M3U file format is a popular way of creating playlists for media players, including IPTV players. These playlists can be used to organize and customize the playback experience of various types of media, including video and audio files, and IPTV streams.

## Table of contents

- [EXT Tags](#ext-tags)
- [TVG Tags](#tvg-tags)
- [Difference between EXT and TVG tags](#difference-between-ext-and-tvg-tags)
- [Difference between ".ts" and ".m3u" files](#difference-between-ts-and-m3u-files)
- [Example](#example)

## Difference between EXT and TVG

TVG and EXT are both types of tags used in M3U playlist files for IPTV streaming, but they serve different purposes.

TVG stands for "TV Guide," and is a type of tag used to provide information about the channel being played, such as its name, logo, and URL. The TVG tags are commonly used by IPTV players to display channel information, and they include TVG-ID, TVG-Logo, TVG-Name, and TVG-URL.

EXT, on the other hand, stands for "extension," and is a type of tag used to add additional functionality to the M3U playlist file. EXT tags are used to specify various parameters for the IPTV stream, such as duration, bandwidth, and resolution. Some examples of EXT tags include EXT-X-VERSION, EXT-X-TARGETDURATION, and EXT-X-MEDIA-SEQUENCE.

## Difference between ".ts" and ".m3u"

The ".ts" file extension refers to the Transport Stream format, which is used for transmitting audio and video data over networks, particularly for IPTV streaming. On the other hand, the ".m3u" file extension refers to an M3U playlist file, which is used to organize and play audio and video files.

## Example

An example of how TVG and EXT tags might be used in an M3U playlist file:

```sh
#EXTM3U
#EXT-X-VERSION:3
#EXT-X-MEDIA-SEQUENCE:0
#EXT-X-TARGETDURATION:11
#EXTINF:10.000000,
http://example.com/stream1.ts
#EXTINF:10.000000,
http://example.com/stream2.ts
#EXTINF:10.000000,
http://example.com/stream3.ts
#EXTINF:10.000000,
http://example.com/stream4.ts
#EXTINF:10.000000,
http://example.com/stream5.ts
#EXTINF:10.000000,
http://example.com/stream6.ts
#EXTINF:10.000000,
http://example.com/stream7.ts
#EXTINF:10.000000,
http://example.com/stream8.ts
#EXTINF:10.000000,
http://example.com/stream9.ts
#EXTINF:10.000000,
http://example.com/stream10.ts
#EXTINF:10.000000,
http://example.com/stream11.ts
#EXT-X-ENDLIST

#EXTINF:10.000000,TVG-ID="Channel1" tvg-name="Channel 1" tvg-logo="http://example.com/channel1.png" group-title="Entertainment",Channel 1
http://example.com/stream1.ts

#EXTINF:10.000000,TVG-ID="Channel2" tvg-name="Channel 2" tvg-logo="http://example.com/channel2.png" group-title="Entertainment",Channel 2
http://example.com/stream2.ts

```

## EXT Tags
| EXT | Meaning |
| --- | ------- |
| #EXTM3U | Indicates that the file is an M3U playlist file |
| #EXTINF | Specifies the duration and title of a media file in the playlist |
| #EXT-X-VERSION | Indicates the version of the HLS protocol used in the playlist |
| #EXT-X-TARGETDURATION | Specifies the maximum duration of any media file in the playlist |
| #EXT-X-MEDIA-SEQUENCE | Specifies the sequence number of the first media file in the playlist |
| #EXT-X-PLAYLIST-TYPE | Indicates the type of playlist, such as "VOD" (video on demand) or "EVENT" |
| #EXT-X-ALLOW-CACHE | Indicates whether the client is allowed to cache the media files |
| #EXT-X-STREAM-INF | Specifies the URI of a variant stream playlist and its properties |
| #EXT-X-MEDIA | Specifies the URI of a media file and its properties |
| #EXT-X-KEY | Specifies encryption information for media files in the playlist |
| #EXT-X-BYTERANGE | Specifies the byte range of a media file in the playlist |
| #EXT-X-DISCONTINUITY | Indicates a discontinuity between two media segments |
| #EXT-X-DISCONTINUITY-SEQUENCE | Specifies the sequence number of the next media file after a discontinuity |
| #EXT-X-PROGRAM-DATE-TIME | Specifies the date and time of the first sample in a media file |
| #EXT-X-INDEPENDENT-SEGMENTS | Indicates whether each media file is a standalone segment or part of a larger media file |
| #EXT-X-ENDLIST | Indicates the end of the playlist |
| #EXT-X-MAP | Specifies the media initialization section for a media file |
| #EXT-X-START | Specifies the time offset and precise start time for a live event |
| #EXT-X-RENDITION-REPORT | Specifies the availability and properties of alternate renditions of a media file |
| #EXT-X-MEDIA-SEQUENCE-DISCONTINUITY | Indicates a discontinuity in the media sequence number |
| #EXT-X-DATERANGE | Specifies a range of dates for a media file or playlist |
| #EXT-X-TARGETDURATION-REACHED | Indicates that the maximum duration of a media file has been reached |
| #EXT-X-SERVER-CONTROL | Specifies server-side control parameters for the playlist |
| #EXT-X-VERSIONING | Specifies versioning information for the playlist |
| #EXT-X-I-FRAMES-ONLY | Indicates that the playlist contains only I-frame media files |
| #EXT-X-INDEPENDENT-SEGMENTS-DISCONTINUITY | Indicates a discontinuity in the independent segments |
| #EXT-X-SESSION-DATA | Specifies arbitrary data associated with the playlist |
| #EXT-X-SESSION-KEY | Specifies encryption information for the entire session |
| #EXT-X-PRELOAD-HINT | Indicates media files that the client should preload |
| #EXT-X-RENDITION-GROUP-ID | Identifies a group of alternate renditions |
| #EXT-X-RENDITION-LANGUAGE | Specifies the language of an alternate rendition |
| #EXT-X-RENDITION-ASSOCIATED-PROPERTY | Specifies a property associated with an alternate rendition |
| #EXT-X-RENDITION-URI | Specifies the URI of an alternate rendition |
| #EXT-X-CUE-OUT | Indicates the start time of a commercial break |
| #EXT-X-CUE-IN | Indicates the end time of a commercial break |
| #EXT-X-RENDITION-GROUP | Identifies a group of alternate renditions |
| #EXT-X-RENDITION-TO-PROGRAM | Specifies the mapping from a rendition to a program |
| #EXT-X-PROGRAM-DATE-TIME-OFFSET | Specifies the offset of the date and time for a live event |
| #EXT-X-CONTENT-IDENTIFIER | Specifies a unique identifier for a media file or playlist |
| #EXT-X-DATERANGE-ID | Specifies the identifier for a date range |
| #EXT-X-SERVER-CONTROL-COMMAND | Specifies a command to be sent to the server |
| #EXT-X-SERVER-CONTROL-HOLD-BACK | Specifies the amount of time to hold back media files |
| #EXT-X-SERVER-CONTROL-PART-HOLD-BACK | Specifies the amount of time to hold back partial media files |
| #EXT-X-SERVER-CONTROL-MAX-DURATION | Specifies the maximum duration of media files to send |
| #EXT-X-SERVER-CONTROL-MAX-AGE | Specifies the maximum age of cached media files |
| #EXT-X-SERVER-CONTROL-CAN-SKIP-UNTIL | Specifies the earliest time to skip to in a media file |
| #EXT-X-SERVER-CONTROL-CAN-SKIP-DATERANGES | Specifies whether the client can skip date ranges |
| #EXT-X-START-DURATION | Specifies the duration of a live event |
| #EXT-X-CUE-OUT-CONT-DURATION | Specifies the duration of a partial cue-out |
| #EXT-X-PROGRAM-DATE-TIME-SERVER | Specifies the date and time of the server |
| #EXT-X-CONTENT-KEY | Specifies a content key for a media file or playlist |
| #EXT-X-DISCONTINUITY-ITEM | Indicates a discontinuity between two media items |
| #EXT-X-SCTE35 | Specifies an SCTE-35 cue message |
| #EXT-X-CUE-OUT-PTS | Indicates the PTS value of a cue-out |
| #EXT-X-CUE-IN-PTS | Indicates the PTS value of a cue-in |
| #EXT-X-CUE-START-PTS | Indicates the PTS value of a cue-start |
| #EXT-X-CUE-END-PTS | Indicates the PTS value of a cue-end |
| #EXT-X-CUE-OUT-CONT-PTS | Indicates the PTS value of a partial cue-out |
| #EXT-X-MEDIA-RENDITION-REPORT | Specifies the availability and properties of alternate media renditions |
| #EXT-X-RELATIVE-CUE-OUT | Indicates the relative start time of a cue-out |
| #EXT-X-RELATIVE-CUE-IN | Indicates the relative end time of a cue-in |
| #EXT-X-RELATIVE-CUE-OUT-CONT | Indicates the relative start time and duration of a partial cue-out. |
| #EXT-X-MAP-BYTERANGE | Specifies the byte range of a media initialization section |
| #EXT-X-CUE-OUT-DURATION | Specifies the duration of a cue-out |
| #EXT-X-CUE-OUT-CONT-ID | Specifies the identifier of a partial cue-out |
| #EXT-X-CUE-IN-DURATION | Specifies the duration of a cue-in |
| #EXT-X-CUE-START-DURATION | Specifies the duration of a cue-start |
| #EXT-X-CUE-END-DURATION | Specifies the duration of a cue-end |
| #EXT-X-CUE-OUT-CONT-DURATION-MS | Specifies the duration of a partial cue-out in milliseconds |

## TVG Tags
| TVG | Meaning |
| --- | ------- |
| TVG-ID | Specifies the unique identifier of the current media file. This tag is used to identify individual channels in the playlist. |
| TVG-NAME | Specifies the name of the current channel. This tag is used to display the name of the channel in the IPTV player. |
| TVG-LOGO | Specifies the URL of the logo for the current channel. This tag is used to display the logo of the channel in the IPTV player. |
| TVG-COUNTRY | Specifies the country code of the current channel. This tag is used to group channels by country in the playlist. |
| TVG-LANGUAGE | Specifies the language code of the current channel. This tag is used to group channels by language in the playlist. |
| TVG-TYPE | Specifies the type of the current channel. This tag is used to group channels by type (e.g. news, sports, entertainment) in the playlist. |
| TVG-URL | Specifies the URL of the website for the current channel. This tag is used to provide additional information about the channel. |
| TVG-GROUP | Specifies the name of the group that the current channel belongs to. This tag is used to group channels in the playlist. |
| TVG-EPGID | Specifies the unique identifier of the electronic program guide (EPG) for the current channel. This tag is used to associate the channel with its program guide. |
| TVG-EPGURL | Specifies the URL of the electronic program guide (EPG) for the current channel. This tag is used to provide the location of the channel's program guide. |
| TVG-EPGSHIFT | Specifies the time shift (in hours) of the electronic program guide (EPG) for the current channel. This tag is used to adjust the program guide for time zone differences. |
| TVG-RADIO | Specifies whether the current channel is a radio channel. This tag is used to differentiate between TV and radio channels in the playlist. |
| TVG-TIMESHIFT | Specifies the time shift (in hours) of the current channel. This tag is used to adjust the channel's start time for time zone differences. |
| TVG-ARCHIVE | Specifies whether the current channel has an archive. This tag is used to indicate whether the channel offers archived content. |
| TVG-TVGPLAYLIST | Specifies the URL of the TVG playlist for the current channel. This tag is used to provide additional playlist information. |
| TVG-ASPECT-RATIO | Specifies the aspect ratio of the current channel. This tag is used to set the aspect ratio for the channel. |
| TVG-AUDIO-TRACK | Specifies the audio track for the current channel. This tag is used to set the audio track for the channel. |
| TVG-CLOSED-CAPTIONS | Specifies whether the current channel has closed captions. This tag is used to indicate whether the channel offers closed captions. |
| TVG-CLOSED-CAPTIONS-LANGUAGE | Specifies the language of the closed captions for the current channel. This tag is used to set the language of the closed captions. |
| TVG-CLOSED-CAPTIONS-TYPE | Specifies the type of the closed captions for the current channel. This tag is used to set the type of the closed captions. |
| TVG-CONTENT-TYPE | Specifies the content type for the current channel. This tag is used to indicate the type of content being broadcast (e.g. movie, TVshow, documentary). |
| TVG-COPYRIGHT | Specifies the copyright information for the current channel. This tag is used to display the copyright information for the channel. |
| TVG-DURATION | Specifies the duration of the current media file. This tag is used to set the duration of the media file. |
| TVG-EXT-X-DISCONTINUITY | Specifies a discontinuity point in the media file. This tag is used to signal a break in the stream. |
| TVG-EXT-X-ENDLIST | Specifies the end of the media file. This tag is used to indicate the end of the playlist. |
| TVG-EXT-X-KEY | Specifies the encryption key for the media file. This tag is used to encrypt the media file. |
| TVG-EXT-X-MEDIA-SEQUENCE | Specifies the sequence number for the media file. This tag is used to indicate the order of the media files in the playlist. |
| TVG-EXT-X-PROGRAM-DATE-TIME | Specifies the date and time of the current media file. This tag is used to synchronize the media file with the program guide. |
| TVG-EXT-X-VERSION | Specifies the version of the M3U8 playlist format being used. This tag is used to indicate the version of the playlist. |
| TVG-GAP | Specifies the time gap (in seconds) between the end of the previous media file and the start of the current media file. This tag is used to synchronize the media files. |
| TVG-INDEPENDENT-SEGMENTS | Specifies whether the media files are independent segments. This tag is used to indicate whether the media files can be played independently. |
| TVG-MEDIA | Specifies the media type for the current media file. This tag is used to indicate the type of media being played (e.g. video, audio). |
| TVG-MEDIA-SEQUENCE | Specifies the sequence number for the media file. This tag is used to indicate the order of the media files in the playlist. |
| TVG-PLAYLIST-TYPE | Specifies the type of playlist being used. This tag is used to indicate whether the playlist is dynamic or static. |
| TVG-START | Specifies the start time (in seconds) for the current media file. This tag is used to set the start time for the media file. |
| TVG-TARGETDURATION | Specifies the maximum duration (in seconds) of the media files. This tag is used to set the maximum duration for the media files. |
| TVG-X-BYTERANGE | Specifies the byte range of the current media file. This tag is used to specify a byte range within a media file. |
| TVG-X-ENDLIST | Specifies the end of the media file. This tag is used to indicate the end of the playlist. |
| TVG-X-KEY | Specifies the encryption key for the media file. This tag is used to encrypt the media file. |
| TVG-X-MEDIA-SEQUENCE | Specifies the sequence number for the media file. This tag is used to indicate the order of the media files in the playlist. |
| TVG-X-PROGRAM-DATE-TIME | Specifies the date and time of the current media file. This tag is used to synchronize the media file with the program guide. |
| TVG-X-VERSION | Specifies the version of the M3U8 playlist format being used. This tag is used to indicate the version of the playlist. |
| TVG-RESOLUTION | Specifies the resolution of the current media file. This tag is used to set the resolution for the media file. |
| TVG-FRAMERATE | Specifies the frame rate of the current media file. |


🙌 For The Community, For The People!



