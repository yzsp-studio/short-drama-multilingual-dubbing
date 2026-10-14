<div align="center">

# 🎬 short-drama-multilingual-dubbing

## 中文短剧换英文，原音色和时长一帧不差
## Keep the original voice and timing — swap Chinese dialogue into English

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

把上传的中文短剧或视频对白重制为目标语言的本土化配音工作流。先提取音轨并分离人声与背景声，识别中文对白并生成只含 start_time 与 duration_sec 的可编辑中英配音表；若用户提供干净人声轨或字幕文件，优先以其作为对白文字与字幕时间基准，没有则先确认是否从视频中提取音频与字幕，并确认目标语言。文本确认后首推逐句音频复刻：截取原中文音频作为参考，在保留音色、情绪、节奏、停顿、强度与时长的基础上替换为目标语言，官方音色作为兜底，混合方案用于个别原句素材不可用的行。最终输出按原时间轴对齐的目标语言配音视频与字幕文件，不改写剧情、不重新设计画面。

### ✨ 能做什么

- 上传视频 → 分离 voice_audio_path 人声轨与 background_audio_path 背景声轨并输出到画布供检查
- 生成只含 start_time / duration_sec 的可编辑中英配音表，不含 speaker、说话人姓名或音色列
- 有字幕文件时直接沿用其中文文案与英文字幕时间戳作为主来源
- 逐句截取原中文音频作为参考，在保留音色、情绪、节奏、停顿、强度与时长下生成目标语言
- 三档方案：音频复刻优先、官方音色兜底、个别不可用行走混合
- 以原视频时间轴为唯一主时钟，输出对齐的英文配音视频与英文字幕文件

### 📦 包含的技能

- `short-drama-multilingual-dubbing` —— 见 [`short-drama-multilingual-dubbing/SKILL.md`](short-drama-multilingual-dubbing/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/short-drama-multilingual-dubbing.git
cp -r short-drama-multilingual-dubbing/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A localization dubbing workflow that re-records uploaded Chinese short-drama or video dialogue in a target language. It extracts the audio, separates voice from background stems, recognizes the Chinese dialogue and builds an editable bilingual dubbing table containing only start_time and duration_sec; if a clean voice track or subtitle file is supplied, that becomes the primary source for dialogue text and subtitle timing, otherwise extraction from the video and the target language are confirmed first. After the text is approved it prioritizes line-level audio replication: each original Chinese line is cut as a reference and replaced in the target language while preserving timbre, emotion, rhythm, pauses, intensity and duration, with official voices as fallback and a mixed approach for lines whose source material is unusable. The output is a target-language dubbed video and subtitle file aligned to the original timeline, without rewriting the plot or redesigning the visuals.

### ✨ What it does

- Uploaded video → separate voice_audio_path and background_audio_path stems, emitted to the canvas for review
- Builds an editable bilingual dubbing table with only start_time and duration_sec — no speaker column, names or voice IDs
- When a subtitle file exists, its Chinese text and English subtitle timestamps are used directly as the primary source
- Cuts each original Chinese line as a reference and regenerates it in the target language while preserving timbre, emotion, rhythm, pauses, intensity and duration
- Three routes: line-level audio replication first, official voices as fallback, mixed handling for individual unusable lines
- Uses the original video timeline as the single master clock and outputs an aligned English dub plus English subtitles

### 📦 Skills included

- `short-drama-multilingual-dubbing` — [`short-drama-multilingual-dubbing/SKILL.md`](short-drama-multilingual-dubbing/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/short-drama-multilingual-dubbing.git
cp -r short-drama-multilingual-dubbing/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
