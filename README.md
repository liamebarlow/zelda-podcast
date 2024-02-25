# zelda-podcast
## Upload MP3s
- Add mp3 files to directory for new shows in directory
- Execute `git add *`
- Execute `git commit -a -m "add new mp3 for episode"` to commit locally.
- Execute `git commit origin main` to push mp3 to servers

## Update Podcast
- Edit podcast_config.yaml
- Execute `./rss_generator.py`
- Execute `git diff` to see changes. Should be sensible.
- Execute `git commit -a -m "add new episode"` to commit locally.
- Execute `git push origin main` to push to servers
- Check RSS is good at https://podba.se/?url=https://liamebarlow.github.io/zelda-podcast/podcast_feed.xml
