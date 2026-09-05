---
name: specialization-media
description: "Generative media point tasks — one per modality and operation — plus one end-to-end production pipeline that carries a brief through to published assets and post-publish metrics."
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: media
  process-count: 7
---

# specialization-media

## Overview

Generative media point tasks — one per modality and operation — plus one end-to-end production pipeline that carries a brief through to published assets and post-publish metrics.

## Available Processes (7)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/media/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `image-editing` (`specializations/media/image-editing`) | Image-editing persona. Analyse source + operation request → select tool |
| `image-generation` (`specializations/media/image-generation`) | Image-generation persona. Parse creative brief → select optimal model |
| `media-production-pipeline` (`specializations/media/media-production-pipeline`) | End-to-end media production: brief → research → script → storyboard → produce → review-gates (editorial, legal, brand) → publish → measure… |
| `music-generation` (`specializations/media/music-generation`) | Music-generation persona. Parse composition brief (genre/mood/duration/instruments) |
| `speech-generation` (`specializations/media/speech-generation`) | Speech-generation persona. Analyse text + voice requirements (language, style, |
| `video-editing` (`specializations/media/video-editing`) | Video-editing persona. Analyse source + request → select tool (Veo Edit, FFmpeg AI, |
| `video-generation` (`specializations/media/video-generation`) | Video-generation persona. Parse request (text-to-video \| image-to-video \| video-to-video) → |

## Subcategories

- `skills/`

## Usage

Use this skill to route work into the `media` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
