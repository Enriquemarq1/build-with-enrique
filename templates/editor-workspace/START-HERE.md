# Your AI editing workspace

Copy this folder to a separate working location. Fill in the brief and style guide, then add your own source media and assets.

```text
editor/workflow.md                 How to do the editing job
styles/my-style/style.md           How you want it to look and feel
styles/my-style/references/        Examples and what to learn from them
assets/                           Fonts, sounds and reusable files
projects/first-video/brief.md      What this video should do
projects/first-video/feedback.md   Corrections for this video
```

Inside the video project, create `source`, `transcript`, `generated`, `edit` and `exports` folders as needed. Source media stays in source; the editable composition stays in edit; review/final video files go in exports. Keep paths explicit.

Ask your agent to read this file, the workflow, the style and the brief. These are ordinary reference documents; this folder layout does not automatically install or register an agent skill. Use your host's supported skill setup if you want a callable style skill that loads these files.

Complete the [setup checklist](../../resources/ai-video-editing/setup.md) in the resource library. If you copied this template alone, find that checklist in the original library.
