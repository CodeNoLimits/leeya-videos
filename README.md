# leeya-videos

Manifest of all video shorts Leeya has generated via Leeya Studio.

**Read** via `https://leeya-studio-bridge.vercel.app/api/videos`
**Write** by the Mac app's orchestrator.py after each successful pipeline run,
via `https://leeya-studio-bridge.vercel.app/api/log-video` (server-side PAT).

## Manifest schema

```json
{
  "videos": [
    {
      "id": "uuid",
      "title": "Le secret du marketing passif",
      "lang": "EN",
      "duration_s": 18.7,
      "youtube_id": "abc123",
      "youtube_url": "https://youtu.be/abc123",
      "thumbnail_url": "https://i.ytimg.com/vi/abc123/hqdefault.jpg",
      "created_at": "2026-05-11T14:23:00Z",
      "source_video": "long_marketing_video.mp4"
    }
  ]
}
```
