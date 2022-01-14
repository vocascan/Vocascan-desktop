# Changelog

This changelog goes through all the changes that have been made in each release on the
[vocascan-desktop](https://github.com/vocascan/vocascan-desktop).

## [v1.1.0](https://github.com/vocascan/vocascan-desktop/releases/tag/v1.1.0) - 2021.11.20

After some time, a new version of Vocascan is coming, with import/export features to share your vocabulary packages and
groups. The invitation codes will help you to keep your server all to yourself and your friends. In addition, we have
tweaked the handling a bit and improved the workflow when creating vocabularies. Feel the magic of the arrow keys
yourself while creating vocabularies.

- Features
  - Import/Export function (vocascan/vocascan-frontend#75)
  - Invite codes (vocascan/vocascan-frontend#77)
  - Show current language on card side while query (vocascan/vocascan-frontend#76)
  - Shortcuts for "add vocab" page. (vocascan/vocascan-frontend#76)
- Bugfixes
  - mac copy/paste shortcuts (vocascan/vocascan-frontend#76)
  - Language selector options visibility (vocascan/vocascan-frontend#73)
  - Min and max lengths for input fields (vocascan/vocascan-frontend#76)
  - Fixed form submit bug for add-vocab screen (vocascan/vocascan-frontend#76)
  - Fixed different animation for logout button (vocascan/vocascan-frontend#76)
  - Improved delay on vocab card flip (vocascan/vocascan-frontend#76)
  - The description is now only on the translated side of the card (vocascan/vocascan-frontend#76)
  - Added translations for "Add"-Button to the select component (vocascan/vocascan-frontend#76)

## [v1.0.0](https://github.com/vocascan/vocascan-desktop/releases/tag/v1.0.0) - 2021.06.13

Finally the time has come. The first release of Vocascan is ready. Vocascan is a server-client vocabulary trainer that
is intended to give the user many setting options so that he can adapt it to his personal learning strategies and
habits. All the basic functions of a vocabulary trainer are currently built in, making it fully functional. However,
there are still many more features to come. Due to the data protection guidelines, we cannot yet provide a public
server, which means that you currently have to host it yourself. But we are working as quickly as possible to use the
trainer offline.

- Basic functions
  - Register/Login
  - Add/modify/delete packages
  - Add/modify/delete groups
  - Add/modify/delete vocabs
  - Start vocab query
  - Decide in which direction the vocabs get queried
  - End-Screen (summary) after query
  - Dashboard
  - Library
  - Languages English, German
  - Guide after register
  - About-page
