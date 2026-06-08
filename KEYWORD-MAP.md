# Keyword Map

## 关键词分组原则

每个关键词只绑定一个主页面，避免站内竞争。工具型关键词优先落到工具页；解释型、对比型和排错型关键词优先落到博客或指南。

## 核心工具词

| Keyword | Intent | Primary URL | Page Type | Priority |
| --- | --- | --- | --- | --- |
| mp3 to wav converter | Convert MP3 to WAV | `/mp3-to-wav` | Tool | P0 |
| wav to mp3 converter | Convert WAV to MP3 | `/wav-to-mp3` | Tool | P0 |
| mp4 to mp3 converter | Extract audio from MP4 | `/mp4-to-mp3` | Tool | P0 |
| m4a to mp3 converter | Convert M4A to MP3 | `/m4a-to-mp3` | Tool | P1 |
| flac to mp3 converter | Convert FLAC to MP3 | `/flac-to-mp3` | Tool | P1 |
| mp3 to flac converter | Convert MP3 to FLAC | `/mp3-to-flac` | Tool | P1 |
| ogg to mp3 converter | Convert OGG to MP3 | `/ogg-to-mp3` | Tool | P1 |
| aac to mp3 converter | Convert AAC to MP3 | `/aac-to-mp3` | Tool | P1 |
| video to audio converter | Extract audio from video | `/video-to-audio` | Tool | P1 |
| audio compressor | Reduce audio file size | `/audio-compressor` | Tool | P0 |
| mp3 cutter | Trim MP3 files | `/mp3-cutter` | Tool | P0 |
| audio joiner | Merge audio files | `/audio-joiner` | Tool | P1 |

## 问题型关键词

| Keyword | Intent | Target Content | Internal Link |
| --- | --- | --- | --- |
| how to convert mp3 to wav | Tutorial | `briefs/blog/how-to-convert-mp3-to-wav.md` | `/mp3-to-wav` |
| how to convert wav to mp3 | Tutorial | `briefs/blog/how-to-convert-wav-to-mp3.md` | `/wav-to-mp3` |
| why is wav larger than mp3 | Explanation | `briefs/blog/wav-vs-mp3-file-size.md` | `/wav-to-mp3` |
| does converting mp3 to wav improve quality | Explanation | `briefs/blog/mp3-to-wav-quality-myth.md` | `/mp3-to-wav` |
| best audio format for podcast | Guide | `briefs/blog/best-audio-format-for-podcast.md` | `/audio-compressor` |
| how to reduce audio file size | Tutorial | `briefs/blog/reduce-audio-file-size.md` | `/audio-compressor` |

## 对比型关键词

| Keyword | Intent | Target Content | Internal Link |
| --- | --- | --- | --- |
| wav vs mp3 | Compare formats | `briefs/blog/wav-vs-mp3.md` | `/mp3-to-wav`, `/wav-to-mp3` |
| flac vs mp3 | Compare formats | `briefs/blog/flac-vs-mp3.md` | `/flac-to-mp3`, `/mp3-to-flac` |
| aac vs mp3 | Compare formats | `briefs/blog/aac-vs-mp3.md` | `/aac-to-mp3`, `/mp3-to-aac` |
| m4a vs mp3 | Compare formats | `briefs/blog/m4a-vs-mp3.md` | `/m4a-to-mp3`, `/mp3-to-m4a` |

## 内容集群

### Audio Conversion Cluster

Hub 页面：

- `/`
- `/mp3-to-wav`
- `/wav-to-mp3`

Supporting pages:

- WAV vs MP3
- MP3 converter complete guide
- Audio quality optimization guide
- Batch audio conversion guide

### Audio Editing Cluster

Hub 页面：

- `/mp3-cutter`
- `/audio-joiner`
- `/audio-compressor`

Supporting pages:

- How to trim MP3 files online
- How to merge audio files
- How to compress audio for podcasts

### Video to Audio Cluster

Hub 页面：

- `/video-to-audio`
- `/mp4-to-mp3`
- `/mov-to-mp3`

Supporting pages:

- How to extract audio from video
- Best audio settings for video extraction
- MP4 to MP3 troubleshooting
