# Changelog

All notable changes to this project will be documented in this file.

## 0.0.27 - 2022-02-14
- **This will do database update**
- Add support for Maimai DX Universe!
- Add new music and event data for O.N.G.E.K.I bright.
- Disable O.N.G.E.K.I bright login announcements.
- Add automatic host and port assignment. Now Aqua works out-of-box without first configuration. Still, previous config entries still works if it needed for some reason. Thanks akiroz!
- Fix rating display in Maimai DX user entry. It now respects ingame rating showing preference as expected.
- Fix Maimai DX user playlog saving. Previously it lost some of data.
- Update O.N.G.E.K.I Aqua API endpoints for user data export and import.

## 0.0.26b - 2021-12-27
- Add new music and event data for O.N.G.E.K.I bright.
- Switch to typical bean name. Previously it was generated dynamically with classpath. No user-side difference.
- Fix tests during build and change default test profile to Sqlite. It was broken since v0.0.17. No user-side difference.
- Update dependencides.

## 0.0.26a - 2021-12-26
- Fix V66 migration - this was critical show-stopper bug in 0.0.26

## 0.0.26 - 2021-12-26 [YANKED]

- **This will do database update**
- Add support for O.N.G.E.K.I bright!
- Disable O.N.G.E.K.I Red Plus login announcements. You can now create new account without numerous event popups.
- Delete some non-user-obtainable cards. This was available in card gacha if you were lucky, and made game crash if you did. Special thanks to htk030 for this.
- Improve some documentations. Like what you seeing right now.
- Fix typo in AimeDB lookup handler.
- Change some mismatches, and delete previous backup tables in Sqlite DB.
- Update dependencies, which includes fixed version for log4j and logback vulnerabilities.

## 0.0.25 - 2021-11-30

- **This will do database update**
- [general] Fix MySQL table initialization error
- [maimai2] Add Splash Plus support

## 0.0.24 - 2021-10-19

- **This will do database update**
- [general] Set maintenance reboot date to far future
- [ongeki] Limit maximum activityList entries
- [maimai2] Add userGeneralData table
- [ongeki] Fix wrong references in user tables
- [maimai2] Implement proper player rate saving
- [maimai2] Fix GetGameEvent Handler to return events to game
- [maimai2] Add game events
- [chuni] Remove unnecessary length info in GetGameRankingApi
- [chuni] Add new music and music level data
- [chuni] Use dynamic reboot time instead of fixed one

## 0.0.23 - 2021-10-06

- [aimedb] Add FeliCaLookup2 mode
- [chuni] Add game data: chara, skill, event, music, music level

## 0.0.22c - 2021-09-28

- [maimai2] Fix play saving on first entry session
- [chuni] Add game data: chara, skill, event, music, music level
- [ongeki] Add game data: event, music

## 0.0.22b - 2021-09-15

- [chuni] Add game data: event, music, music level
- [ongeki] Add game data: event, music

## 0.0.22a - 2021-08-30

- [ongeki] Add game data: event, music

## 0.0.22 - 2021-08-30

- **This will do database update**
- [chuni] Implement GetGameRankingApi
- [maimai2] Enable isNetUser and implement UploadUserPhotoApi
- [maimai2] Implement GetGameEventApi and UploadUserPlaylogApi
- [chuni] Add game data: chara, skill, event, music, music level

## 0.0.21 - 2021-08-19

- **This will do database update**
- [general] Update to Spring Boot 2.5
- [maimai2] Experimental Splash Plus Support

## 0.0.20a - 2021-08-17

- [chuni] Add game data: chara, skill, event, music, music level

## 0.0.20 - 2021-08-17

- **This will do database update**
- [chuni] Fix: make event popup to not show
- [ongeki] Add table properties for Red Plus
- [maimai2] Fix play record saving when guest is involved

## 0.0.19e - 2021-08-04

- [chuni] Add game data: chara, skill, event, music, music level
- [ongeki] Add game data: event, music

## 0.0.19d - 2021-07-20

- [chuni] Add game data: chara, skill, event, music, music level

## 0.0.19c - 2021-07-10

- [maimai2] Fix incorrect scope during save UserRating

## 0.0.19b - 2021-07-07

- [chuni] Add game data: event, music, music level

## 0.0.19a - 2021-07-01

- **This will do database update**
- [ongeki] Add game data: card, music, event
- [ongeki] Fix judgement offset saving

## 0.0.19 - 2021-06-28

- **This will do database update**
- [chuni] Add missing data: skill, character, music, music level
- [ongeki] Add missing data: card, character, music, event
- [ongeki] Add proper endpoint for new APIs
- [chuni] Add team name customization feature
- [api] Fix broken chunithm API

## 0.0.18 - 2021-06-25

- [ONGEKI] Add support for ONGEKI Red Plus

## 0.0.17 - 2021-06-19

This was the first forked version release.

- **This will do database update**
- [maimai2] Add support for Maimai DX Splash
- [chuni] Enable standard course and team function
- [chuni] Add support for CHUNITHM Paradise Lost
- [maimai] Add Maimai Finale support

## 0.0.16

- **This will do database update**
- [chuni] Add support for CHUNITHM Amazon Plus
- [chuni] Support auto profile downgrade now.
- [ONGEKI] Fix jewel not being saved (bbs)
- [ONGEKI] Better choKaika method (bbs)

## 0.0.15

- [ONGEKI] Add support for ONGEKI Summer

## 0.0.14

- [general] Reduce connection pool size to 1 to prevent dead lock with sqlite
- [ONGEKI & chuni] Fix score missing again
- [chuni] Read reboot time from database
- [api] Set level to max when chouKaika a card

## 0.0.13

- **This will do database update**
- [ONGEKI & chuni] Fix rating drop
- [aimedb] Allow bind to specific interface
- [API] Allow export and import ongeki and chuni profile. More feature to chuni's api

## 0.0.12

- [ONGEKI] Save UserMissionPoint, UserTrainingRoom, UserGeneralData, GamePoint, GamePresent, GameReward to database
- [ONGEKI] Add custom maintenance time to database
- [ONGEKI] Save the battle point and rating info send by the game to database
- [API] Read database from general table

## 0.0.11a

- [API] Add more ongeki feature

## 0.0.11

- **This will do database update**
- [ONGEKI] Add support to ongeki plus

## 0.0.10

- **This will do database update**
- [DIVA] Add mega39's pv list
- [DIVA] Configurable contest pv limit and reward
- [chuni] Add all old version event
- [chuni] Disable all type 1 event by default
- [chuni] Allow game version overwrite to play the same profile across all version

## 0.0.9

- **This will do database update**
- [API] Fix rating fail to calculate due to lack of music level info
- [API] Move diva music list to database
- [DIVA] Fix continue not work
- [DIVA] Clear status now will count lower clear rank

## 0.0.8

- **This will do database update**
- [chuni] Fix a course table column
- [API] Force unlock diva session
- [API] Get screenshot

## 0.0.7

- **This will do database update**
- [chuni] Add basic support to old release
- [DIVA] Fix wrong name is being sent to the ranking
- [DIVA] Fix exex ranking not being return.
- [DIVA] Fix wrong contest progress is being sent
- [DIVA] Add stage result index to prevent multiple result being sent by client, fix #3
- [aimedb] Prevent same access code being register multiple times
- [allnet] Fix host header

## 0.0.6

- **This will do database update**
- [DIVA] Replace with correct pv list databank
- [DIVA] fix stage_result placeholder to the correct length, level up animation is now working
- [DIVA] Rival support and configurable border.
- [DIVA] Fix ranking being reversed
- [API] Allow edit diva rival and new border type

## 0.0.5

- **This will do database update**
- [aimedb] fix some card number causing overflow
- [chuni] fix unique key constraint , fix #1
- [API] allow input space in aime request

## 0.0.4

- [chuni] Fix user item being overwritten
- [API] Fix record id not being return.

## 0.0.3

- Add database migration tool. If you are running on a old version, I encourage you to delete the old database and generate a new one.
