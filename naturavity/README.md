# Naturavity

**Find people to share outdoor activities with, in Romania.**

Naturavity is a mobile app that connects people for outdoor sports and activities: skiing, cycling, running, hiking and more. Pick a sport, browse events and groups near you, and join people at your level.

> **Status: early development.** The project is in the design phase. Nothing below is shipped yet, the roadmap shows what is planned and what is done.

---

## The problem

You want to go skiing at Poiana Brașov on Saturday, or ride the Transfăgărășan, but your friends are busy or not at your level. Today you end up searching scattered Facebook groups and chats, with no easy way to know who is organizing, who is joining, or whether the group is trustworthy.

## The idea

One place where outdoor people in Romania can:

- **Choose a sport** at first launch and get a feed tailored to it
- **Discover events and groups** for that sport, filtered by area, date and skill level
- **Join an event** with one tap and chat with the other participants
- **Trust who they meet** through verified organizers, ratings and reporting tools
- **Switch sports quickly** from a long-press menu, Instagram-style navigation with a sport-first twist

Later, each sport gets its own features, for example a running tracker with pace comparison between participants, or a speed tracker for skiing.

## Scope

Naturavity is for **outdoor activities in Romania**. This is intentional: a narrow focus keeps the project buildable and the community relevant. Indoor and non-outdoor activities are out of scope.

## Planned MVP

| Feature | Description |
|---|---|
| Accounts | Sign up and log in |
| Profile | Name, sports, skill level (beginner / intermediate / advanced) |
| Sport selection | Choose a sport at onboarding, switch later from the menu |
| Events | Create an event with sport, location, date, level and number of spots |
| Feed | Browse events and groups, filtered by sport, area and date |
| Join | Join or leave an event, see participants |
| Event chat | Simple chat inside each event |

Not in the MVP: trackers, leaderboards, stories, photo feed.

## Safety and trust

Meeting strangers for outdoor activities carries real risk, so safety is part of the design from the start. No system can guarantee safety, so Naturavity aims to reduce risk in layers:

- **18+ only**
- **Verified accounts** (email and phone number)
- **Verified organizers** with a visible badge, approved manually at first (clubs, ski schools, guides)
- **Ratings and reviews** after events
- **Report and block** on every profile, post and message
- **Chat only inside events**, no private messages between strangers at the start
- **Safety tips** shown before joining an event

## Tech stack (planned)

| Layer | Technology |
|---|---|
| Mobile app | React Native with Expo (JavaScript/TypeScript) |
| Backend API | Python, FastAPI |
| Database | PostgreSQL (with PostGIS for location search) |
| Auth | Token-based (JWT) |

## Roadmap

- [ ] Database schema and design
- [ ] Backend API: users, events, participation
- [ ] Mobile app: onboarding, feed, event page
- [ ] Deployment and first test users
- [ ] Event chat and notifications
- [ ] Verified organizers and reporting
- [ ] Per-sport trackers (running first, then skiing and cycling)

## Repository structure (planned)

```
naturavity/
├── backend/    # FastAPI server and database
├── mobile/     # React Native (Expo) app
└── docs/       # Design notes and database schema
```

## Why this project

I am a Computer Science student building Naturavity to learn how a complete application is designed and built, from database and API to a mobile app used by real people. The code is open source so the process is visible, from the first schema to the final release.

## Author

Built by Tudor ([@TudorDik](https://github.com/TudorDik)).

## License

To be decided.
