# drawsprint
[README_1.md](https://github.com/user-attachments/files/29361802/README_1.md)

# DrawSprint ✏️

A gesture drawing practice tool for artists. Open it, draw. No menus, no friction.

## What it does

DrawSprint drops you straight into a timed drawing session — a random category, a random timer, a random number of images. All pulled from Pexels's professional photo library and mixed with your own personal reference images.

- **Timed sessions** — 15s to 5 minutes per image
- **Categories** — Faces, Hands, Poses, Full figure, Expressions
- **Zoom & pan** — scroll to zoom, drag to move around the reference
- **Personal library** — upload your own reference images, saved permanently in the browser
- **Quick controls** — arrow buttons to cycle category and time on the fly
- **Custom popup** — set category, time and image count manually mid-session
- **Multilingual** — IT / EN / ES / FR
- **Text size** — S / M / L scaling for the interface

## How to run it locally

1. Clone or download this repository
2. Put your own reference images in the `images/` folder
3. Open `DrawSprint_v3.html` in any browser — no server needed

## Adding your own images

Open `DrawSprint_v3.html` in a text editor, find the `MY_IMAGES` array and add your file paths:

```javascript
const MY_IMAGES = [
  'images/hand-study-01.jpg',
  'images/face-ref-02.jpg',
];
```

## API key

The project uses the [Pexels API](https://www.pexels.com/api/) for reference photos. The key in the file is for personal use — if you fork this project, replace it with your own (free).

## License

MIT — use it, modify it, share it.
