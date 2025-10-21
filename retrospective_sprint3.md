# Sprint 3 Retrospective

## What went well in the previous sprint?
- I refactored KoreanMusic page which configured the architecture of useKoreanMusics hook -> koreanMusicService service -> koreanMusicRepo repository -> mockKoreanMusics test data. The data stays when you move to another page because of useState.
- I implemented Contact feature with EmailJS for email sending. It allowis end users to send inquiries to admins via a simple form. It used form components to deliver content in an organized layout.
- I implemented MusicPlayerBar which configured the architecture of useYouTubeMusicsList hook -> YouTubeMusicsListService service -> YouTubeMusicsListRepo repository -> youtubeMusicsList test data. It uses react-youtube to play music via YouTube video IDs.
- I wrote comment blocks for key components which is MusicPlayerBar, KoreanMusic, Login, and Contact. They explain how each component is configured and why it was created for the application.

## What could have gone better in the previous sprint, or went poorly?
- Now, The music player uses react-youtube which fetches videos. It is very slow to load music. This can reduce the user experience. In the future, I consider using a music audio API for seamless playback.
- Now, The music player bar lacks volume and duration controls. It reduces user experience in a music app. In the future, additional control options should be added to improve usability.

## What can be done in the next sprint to do better?
- I will integrate SQL Database and design the schema which is based on the current 4 test data (mockChineseMusics, mockFilipinoMusics, mockKoreanMusics, and youtubeMusicsList) for unified management.
- I will add CORS middleware to ensure only allowed URLs can access the backend for enhanced security.
- I will add a Node.js Express based backend to integrate an SQL database and music audio API.
