# Presentations2Go
This building block provides a Presentations2Go integration with Blackboard.

This building block requires a license key. Please contact info@presentations2go.eu if you are interested in using this building block.

## Links
- [Download Latest Release](https://github.com/rijksuniversiteit-groningen/b2-Presentations2Go/releases/latest)
- [View All Releases](https://github.com/rijksuniversiteit-groningen/b2-Presentations2Go/releases)

## Release Notes

### 3000.171219.1
- added simple HTML5 video player as a mashup option
- added simple HTML5 audio player as a mashup option, requires Presentations version 5 or later, case 179369
- fixed "TEMPORARY scope is unavailable." exception when someone who is not logged in (anymore) tries to view a list of videos
- fixed "bean playbackUrl not found within scope" exception when creating a text link mashup, case 237751
- fixed upload attributes defined in the repository not being used in assignments, case 228294

### 3000.171120.0
- support multiple/different repositories for video assignments, case 230196
- variables like ${user.email} are now supported for configuring the upload user

### 3000.170530.1
- New (simple) mashup player for use in exams.
- Video assignments; only one attempt allowed for the moment.
