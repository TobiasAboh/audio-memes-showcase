# AudioMemes

**AudioMemes is like Tenor, but for audio memes instead.** It's a platform concept focused on discovering, sharing, and playing funny audio clips—bringing the quick, searchable meme experience people know from GIF platforms to sound.

> **Testing status:** The Android app is currently in **closed testing on Google Play**. Access is limited to approved testers.

## Try AudioMemes

Interested in testing the Android app? **[Register to become an AudioMemes tester](https://forms.gle/u4C2mkCg7CzPj5Wf6)**. I'll add approved testers to the testing programme and share the instructions for opting in.

Already added to the tester list? [Open AudioMemes on Google Play](https://play.google.com/store/apps/details?id=com.tobias.audio_memes).

*Submitting the form does not grant immediate access. You'll need to be added to the tester list and opt in to the closed test before installing.*

This repository is the **public project showcase** for AudioMemes and its related ecosystem. The production application's source code is maintained privately.

## The AudioMemes ecosystem

### 🎧 AudioMemes platform
The core product is an audio-meme discovery and playback experience. The application is built with a React Native / Expo client and a Go backend using Gin, with PostgreSQL for data and AWS S3 for audio-object storage.

### 🔌 AudioMemes SaaS API
AudioMemes also has a SaaS API that exposes AudioMemes functionality to other integrations. It allows separate applications and bots to build on the AudioMemes ecosystem without being the main mobile app.

### 🤖 AudioMemes Discord bot
I built a Discord bot that uses the AudioMemes SaaS API, bringing AudioMemes into Discord communities.

**[Add the AudioMemes bot to Discord](https://discord.com/oauth2/authorize?client_id=1558771955774132315)**

## Engineering highlights

- **Mobile application:** React Native, Expo, and TypeScript
- **Backend services:** Go and Gin
- **Data layer:** PostgreSQL
- **Audio storage:** AWS S3
- **Integrations:** SaaS API and a Discord bot client
- **Product architecture:** one audio-meme platform with multiple ways to access and integrate its capabilities

## Why this project matters

AudioMemes is more than a standalone app: the platform, API, and Discord bot form a small product ecosystem. Building connected clients and integrations involves thinking about API design, data persistence, object storage, and how one service can support different user experiences.

## Source code and privacy

This repository is intended to document the product and its architecture for portfolio and professional review. It is **not** the source repository for the production application, SaaS API, or Discord bot. Those implementations are kept private.

## Links

- **Project showcase:** [audio-memes-showcase](https://github.com/TobiasAboh/audio-memes-showcase)
- **Tester registration:** [Join the AudioMemes closed test](https://forms.gle/u4C2mkCg7CzPj5Wf6)
- **Google Play listing:** [AudioMemes on Google Play](https://play.google.com/store/apps/details?id=com.tobias.audio_memes)
- **Discord bot invite:** [Add AudioMemes to your server](https://discord.com/oauth2/authorize?client_id=1558771955774132315)

---

*Built as an interconnected audio-meme product: like Tenor, but for audio memes instead.*