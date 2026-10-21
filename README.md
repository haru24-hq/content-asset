# content-asset

Public host for published video files, served through jsDelivr.
One folder per channel, one folder per post date.

    <channel>/<YYYY-MM-DD>/video.mp4 + post.json

Written by the daily generation task; read by the Make publish scenarios.
Not a media archive — migration to object storage is tracked in life-os `todo.md`.
