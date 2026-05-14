# fukui-kanko-hackathon-20230107

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

This repository archives the materials from a civic tech introduction and ideathon held on January 7, 2023. The event was designed for high school and technical college students, focusing on enhancing Fukui Prefecture's tourism experiences through data analysis. Student teams presented solutions for local tourist spots, such as a QR-code-based information system for Tōjinbō.

## Live Demo

The event's recordings, photos, and materials are presented on a static web page hosted on GitHub Pages.

- **[Event Archive Page](https://code4fukui.github.io/fukui-kanko-hackathon-20230107/)**
- [Original Event Announcement (Peatix)](https://fukuidx1.peatix.com/)

## Repository Contents

The `index.html` file serves as a simple, single-page archive with collapsible sections for the following media:

- **Team Presentations:** Videos of each team's final presentation (`teamA.mp4`, `teamB.mp4`, etc.).
- **"Kids Safe" Workshop:** Photos and a short video from the workshop activities, located in the `kidssafe/` directory.
- **360° Venue Photo:** An interactive 360° panorama of the event venue, powered by A-Frame. The viewer is `group-photo/index.html`.
- **Group Photos:** Photos of the participating teams and a final group shot, located in the `group-photo/` directory.

## Development

To view the archive page locally, open `index.html` in a web browser.

### Video Encoding

The raw video files were converted to a web-friendly MP4 format (960x540) using FFmpeg. This command reduces a 2-minute video to approximately 10MB.

```sh
ffmpeg -i input.MOV -vf scale=-1:540 output.mp4
```

## License

[MIT License](LICENSE)