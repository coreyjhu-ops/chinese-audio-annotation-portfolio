# 04 Chinese Accent Awareness - Annotated Transcript

## Audio Metadata

- File: `04.m4a`
- Language: Mandarin Chinese
- Duration: 33.62 seconds
- Format: mono AAC, 48 kHz
- Peak level: -7.6 dBFS
- RMS level: -34.5 dBFS
- Estimated noise floor: -69.0 dBFS
- Clipping: none detected
- Verification status: transcript drafted from recording script; speaker review recommended

## Verbatim Transcript

中文语音里的地区差异不一定会影响理解，但会影响标注和模型训练。例如，有些说话人会把平翘舌区分得不明显，有些地区的普通话会在声调、儿化音或者韵母上保留地方习惯。做标注时，我会避免把这些差异简单判断为错误，而是先看它们是否改变语义，再决定是记录为口音特征、发音变体，还是需要标为不确定。

## Normalized Transcript

中文地区差异不一定影响理解，但会影响标注和模型训练。标注时应区分语义错误、口音特征、发音变体和不确定片段，避免把地区性发音差异简单判为错误。

## Prosody Notes

| Timestamp | Feature | Observation | Annotation decision |
|---|---|---|---|
| 00:00-00:08 | framing | Introduces distinction between comprehension and annotation | Mark as key conceptual contrast |
| 00:09-00:23 | examples | 平翘舌, 声调, 儿化音, 韵母 | Mark list structure |
| 00:24-00:34 | judgment rule | Decide based on semantic impact first | Mark decision principle |

## Audio Quality Notes

| Dimension | Rating | Evidence |
|---|---|---|
| Background noise | Low | Estimated floor around -69.0 dBFS |
| Clipping | None | 0.0% clipping detected |
| Volume stability | Good | Highest peak among samples, still safe at -7.6 dBFS |
| Training usability | Good | Directly maps to JD accent/regional-variation requirement |

## Final Annotation Decision

Accept. This is one of the most strategically important samples because it shows linguistic judgment rather than only pronunciation.

