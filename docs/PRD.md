# 🎵 SpotiAI – Product Requirements Document (PRD)

---

## 1. Problem Statement
Today, Spotify users can view Wrapped once a year to reflect on their listening history.  
However, users **cannot interact dynamically** with their music and podcast data,  
nor can they extract **personalized, bite-sized learning** from podcast episodes they’ve listened to.

There is a growing demand for **personal, conversational experiences** tied to content consumption —  
**SpotiAI** fills this gap by enabling users to **chat** with their listening history and get **micro-summaries** from podcasts they engage with.

---

## 2. Target Users
| Persona | Description |
|---------|-------------|
| The Music Explorer | Loves discovering new artists and wants to understand their music journey. |
| The Podcast Learner | Listens to podcasts for personal growth and wants quick learning summaries. |
| The Data Curious | Loves statistics and insights about their own behavior and habits. |
| Social Sharer | Enjoys sharing Spotify insights and moments on social media. |

---

## 3. Goals and Objectives
- Provide a **conversational interface** for Spotify listening data.
- Deliver **personalized podcast micro-summaries** based on episodes actually listened to.
- Increase user **engagement**, **retention**, and **time spent** inside the app.
- Strengthen Spotify’s brand image as a **leader in personalized audio experiences**.

---

## 4. Features (MVP Scope)

### 4.1 Conversational Music Insights
- Users can ask questions like:
  - "How many hours did I listen to music this month?"
  - "What new artists did I discover this year?"
- System fetches relevant data and responds in natural language.

### 4.2 Podcast Micro-Summaries
- After listening to an episode, users can ask:
  - "What was the main takeaway from today's episode?"
- AI generates a **short, headline-style** summary ONLY if the user listened to the episode.

### 4.3 Personal Listening Dashboard (Optional MVP+)
- View high-level stats like total minutes, top genres, mood-based music trends.

---

## 5. Out of Scope (for MVP)
- Real-time live chat with music recommendations (future)
- Mood detection from listening behavior (future)
- Automatic emotional journaling based on songs (future)

---

## 6. User Stories

| As a... | I want to... | So that... |
|---------|--------------|------------|
| Music Explorer | Ask how much time I spent listening this month | I can reflect on my music habits |
| Podcast Learner | Get a short summary of podcasts I've listened to | I can easily recall and share learnings |
| Data Curious | Explore my top artists and genres via chat | I can see how my tastes evolved |
| Social Sharer | Share cool facts about my listening | I can engage friends and showcase my Spotify journey |

---

## 7. Success Metrics

| Metric | Target |
|--------|--------|
| Chat Engagement Rate | % of users starting a chat session |
| Session Duration | Avg. time spent interacting with SpotiAI |
| Retention Rate | % of users returning weekly to check SpotiAI |
| Podcast Summary Usage | % of podcast listeners requesting summaries |
| NPS (Feature-specific) | Net Promoter Score for SpotiAI experience |

---

## 8. Technical Considerations

| Aspect | Details |
|--------|---------|
| Spotify API Integration | OAuth login, listening history fetch |
| OpenAI API Integration | Text summarization engine for podcasts |
| Database | Secure storage of listening sessions (optional if needed) |
| Privacy | Only analyze data from episodes the user has listened to |

---

## 9. Roadmap

| Version | Focus |
|---------|-------|
| V1 (MVP) | Conversational music insights + Podcast Micro-Summaries |
| V2 | Emotional trend analysis ("Songs when sad", "Happy playlists") |
| V3 | Predictive recommendations based on listening behavior |

---

## 10. Risks and Mitigation

| Risk | Mitigation |
|------|------------|
| Low adoption | Launch with Wrapped marketing campaign |
| Privacy concerns | Clear opt-in, explain data usage |
| Summarization quality | Human QA on early models or fine-tuning |

---

## 11. Appendix
- Spotify API Documentation (linked)
- OpenAI GPT API Documentation (linked)
- Figma Wireframes (linked when ready)

---
