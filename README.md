# Sync Audio Player
Author: OhGeezCmon

Description: Syncs BUILT IN Audio across clients.

Originally built back in the SDK2 days where I wanted multiple dance rooms in a world but couldn't have more than one SyncVideo player going at a time. Updated to Udon and it has much more accurate syncing, down to the second.

Dependencies: 
- [Udon#](https://github.com/MerlinVR/UdonSharp) (Not Included)
- [VRCSDK3-WORLD](https://vrchat.com/home/download) (Not Included)

## Installation Guide
Simply download and import the latest **Unity Package** from [**Releases**](https://github.com/OhGeezCmon/VRC-SyncAudioPlayer/releases) on GitHub

## How to Use
- Expand "Play List" on Prefab and set to your desired playlist length.  Attach supported Unity sound files to the playlist.
- If you want to change how often and how accurate your sync is, adjust the Sync Duration and Sync Threshold values respectively.  They are in seconds.  Defaults should be fine for most applications.

## Common Questions
**Does this support YouTube/Twitch/etc?**
>Not at the moment. It's only for audio files that already exist in your Unity project.  If you want something that streams you should look at UdonSyncPlayer.  I might look into a streaming solution if there is enough interest.

**Can I disable auto loop?**
>Not yet. Once a playlist completes it'll go back to track 1 and start over.  I'll add a future update to make it configurable.

## Contacting Me
Feel free to contact me on Discord (OhGeezCmon#7104) or leave a suggestion or issue on the [Issues](https://github.com/OhGeezCmon/VRC-SyncAudioPlayer/issues) page.