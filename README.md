# Jose Villalba

Builder-investor. I build and run a personal multi-agent AI system on Claude Code every day.

The repos here are finished work samples pulled out of that private system. Each one started as a real problem I hit while running it. I fixed it, wrote it up, and kept the repo small on purpose.

| Repo | Problem | What it does |
|---|---|---|
| [resumable-fanout](https://github.com/Josevventures/resumable-fanout) | A parallel subagent dispatch silently dropped work partway through a run. There was no error and no way to tell which piece was lost. | Checkpointed, capped-concurrency dispatch with crash recovery and a single deterministic reducer that is the only thing allowed to merge results. |
| [audio-debrief](https://github.com/Josevventures/audio-debrief) | Standard diarization silently lost the far-side speaker on phone-captured calls. | Offline transcript plus delivery metrics, built on a hybrid Whisper-VAD and speaker-embedding diarizer that picks up the far-side speaker. |

The system itself isn't public. I'm on [LinkedIn](https://www.linkedin.com/in/joselvillalba/).
