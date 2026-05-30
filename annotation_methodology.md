# Annotation Methodology

## Principle

The annotation process separates what was said from how it was said. A transcript captures lexical content, while audio annotation should preserve signals that matter for multilingual speech systems: pauses, stress, intonation, rhythm, background noise, uncertainty, and accent or pronunciation variation.

## Layers

1. Verbatim transcript: exact spoken content, including meaningful fillers, repetitions, repairs, or false starts.
2. Normalized transcript: cleaned version for readability when it does not remove meaning.
3. Prosody notes: timing, pause structure, stress, intonation, pace, and emotional tone.
4. Audio quality notes: noise, clipping, volume stability, reverb, distance from microphone, and intelligibility.
5. Ambiguity log: uncertain words or segments, possible interpretations, and final decision.

## Decision Rules

- Do not guess when speech is unclear.
- Mark uncertainty explicitly when a segment cannot be reliably transcribed.
- Do not treat regional pronunciation as an error unless it changes meaning or violates task guidelines.
- Separate speaker accent from audio-quality issues.
- Prefer consistent labels over overly detailed one-off labels.
- Keep reviewer comments concise and evidence-based.

## Prosody Labels

- `pause_short`
- `pause_long`
- `stress`
- `rising_intonation`
- `falling_intonation`
- `fast_speech`
- `slow_speech`
- `self_correction`
- `filler`
- `repetition`
- `uncertain`
- `background_noise`
- `overlap`

## Quality Rubric

| Score | Label | Definition |
|---|---|---|
| 5 | Excellent | Clear voice, low noise, stable volume, natural delivery |
| 4 | Good | Minor noise or minor delivery issues, still reliable |
| 3 | Usable with notes | Understandable but has noise, uneven volume, low volume, or mild ambiguity |
| 2 | Needs review | Multiple uncertain segments; transcript may be incomplete |
| 1 | Reject | Too noisy, clipped, or unclear for reliable annotation |

