# Naturavity

**Find people to go outdoors with, in Romania.**

Naturavity is a mobile app for finding people to share outdoor activities with: skiing, cycling, running, hiking and more. Pick a sport, see who's going out near you, and join.

> **Status:** early development. I'm still in the design phase, so nothing here is built yet. The roadmap below shows where I am.

## Why I'm building this

Every weekend there's a good chance to go skiing at Poiana Brașov or ride the Transfăgărășan, and every weekend someone has nobody to go with. Right now that means digging through scattered Facebook groups and hoping the people are who they say they are. I want one place that does this properly.

## How it works

- You pick a sport when you open the app and get a feed for it
- You browse events and groups filtered by area, date and skill level
- You join with one tap and chat with the others going
- A long press on a button opens a quick menu to switch sports

Later, each sport gets its own tools, like a pace tracker for running or a speed tracker for skiing.

## Scope

Outdoor activities in Romania, nothing else. I'm keeping it narrow on purpose, so the project stays something I can actually finish.

## First version (MVP)

- Sign up and log in
- A simple profile with your sports and level
- Create an event (sport, place, date, level, number of spots)
- A feed of events, filtered by sport, area and date
- Join an event and see who's coming
- A basic chat for each event

No trackers or leaderboards yet. Those come after the basics work.

## Safety

Meeting strangers is a real risk, and no app can promise to remove it. What I plan to do is reduce it:

- 18+ only
- Verified accounts (email and phone)
- Verified organizers with a badge, approved by hand at first
- Ratings after events
- Report and block on everything
- Chat only inside events, no private messages between strangers

## Tech stack (planned)

- **Mobile:** React Native with Expo
- **Backend:** Python with FastAPI
- **Database:** PostgreSQL (with PostGIS for location search)

## Roadmap

- [ ] Database schema
- [ ] Backend API (users, events, joining)
- [ ] Mobile app (onboarding, feed, event page)
- [ ] First test users
- [ ] Event chat and notifications
- [ ] Verified organizers and reporting
- [ ] Sport trackers (running first)

## About me

I'm a Computer Science student building this to learn how a real app comes together, from the database to the phone screen. The code is open so you can follow along as it grows.

Built by Tudor ([@TudorDik](https://github.com/TudorDik)).
