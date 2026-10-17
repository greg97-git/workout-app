# F45 Home Workout — exercise demo videos

The workout app runs without videos. Its video panel is ready to play MP4 files from the `videos/` folder, but no third-party exercise footage has been uploaded yet.

## Approved candidate source

[Your Move — Free Exercise Videos](https://ymove.app/free-exercise-videos) expressly permits its 25 free MP4 demos in websites and apps, including commercial use; it prohibits resale or redistribution as a standalone video library. Always double-check the current terms before uploading.

From this collection, the workout currently has these exact or close-enough demo candidates:

| Workout movement | Your Move clip | Save as |
| --- | --- | --- |
| Station 3A, kettlebell swing (wife's variation) | Kettlebell swing | `videos/kettlebell-swing.mp4` |
| Station 3C, kettlebell goblet squat (wife's variation) | Goblet Squat with Dumbbell | `videos/goblet-squat-dumbbell.mp4` |
| Station 4C, single-arm bent-over row | Single Arm Dumbbell Row - Legs apart | `videos/single-arm-dumbbell-row.mp4` |

**Equipment caveat:** Station 3 demos illustrate kettlebell technique, not the man's dumbbell substitute. Don't treat them as instructions for an unfamiliar dumbbell swing.

## Installation

1. On [Your Move](https://ymove.app/free-exercise-videos), download the three matching free MP4 clips.
2. In your GitHub repository, select **Add file → Upload files**, upload them to the `videos/` directory under the precise names above, and commit.
3. Reload the [workout app](https://greg97-git.github.io/workout-app/). The matching demos should autoplay muted and loop during those exercises.

GitHub's web file uploader may need you to create the `videos` folder first (for example by adding `videos/README.md`), or you can upload the clips in one commit with a Git client.

All other exercises currently display placeholders. Never substitute a technically different movement merely to fill a video slot. Additional footage should only be added after confirming the movement and permission to host it publicly.

**Privacy:** No photos or recordings of the household are needed or included.

## User-provided clips (October 2026)

The owner supplied three MP4 recordings to be uploaded under `videos/`. Prepared names: `kettlebell-swing.mp4`, `goblet-squat-dumbbell.mp4`, and `single-arm-dumbbell-row.mp4`. These are not currently committed via the connector; download the prepared ZIP, extract it, then drag the **videos folder** into the repository's **Add file → Upload files** page, or use a desktop Git client. Commit the three MP4 files, then reload the Pages website. The goblet-squat clip uses a **dumbbell**, not a kettlebell. Source/license provenance has not been verified independently for the uploaded recordings.
