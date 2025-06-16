# ClipWise

**ClipWise** is an open-source tool that uses AI to automatically create short-form clips from long videos. It transcribes videos, detects highlights, and helps users repurpose content quickly for social media platforms.

## Features (Roadmap)
- [x] Upload long-form videos
- [x] Transcribe audio using AI (OpenAI Whisper)
- [ ] Automatically detect and extract interesting moments
- [ ] Export clips in TikTok/Shorts/Reels format
- [ ] Simple web interface for uploads and downloads

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/ClipWise.git
   cd ClipWise
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   python -m clipwise.main
   ```

## Directory Structure

```
ClipWise/
├── README.md
├── requirements.txt
├── clipwise/
│   ├── __init__.py
│   ├── main.py
│   ├── video_processing.py
│   ├── transcription.py
│   └── utils.py
├── data/
│   ├── uploads/
│   └── transcriptions/
├── .gitignore
└── LICENSE
```

- `clipwise/` — All main code modules
- `data/uploads/` — Uploaded videos (not tracked by git)
- `data/transcriptions/` — Transcription outputs (not tracked by git)

## Contributing

Pull requests and discussions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) (to be created).

## License

[MIT](LICENSE)
