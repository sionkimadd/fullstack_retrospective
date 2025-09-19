# Sprint 1 Retrospective

## What went well in the previous sprint?
- I implemented `Router` feature with "react-router-dom". So, I could seperate each page such as `/`, `/KoreanMusic`, and `/ChineseMusic`. This Router has explandable structure because I can add more pages easily and auth feature in the future.
- I imported `KoreanMusicList.json` and rendered the list of Korean songs on the `/KoreanMusic` page with a map function. The json file has two parameters, `title` and `artist`. So, I could display the list of songs with title and artist.
- I imported GoogleFonts `Inter` and created different font styles by `font-weight` values. I could apply the font styles to `className` property. It improved the overall typography of the project.

## What could have gone better in the previous sprint, or went poorly?
- Now, the `KoreanMusic.json` files is imported as static data. So, it is hard to update or add new songs in the future. I need to change load way of the json from static to dynamic.
- Although I created several font styles with different `font-weight` values, I could not establish clear guidelines for when and where each style should be used. This resulted in inconsistent typography across the project.

## What can be done in the next sprint to do better?
- I will change load way of the `KoreanMusic.json` file from static to dynamic because I want to add new songs with form.
- I will add expand and collapse feature to the song list on the `/KoreanMusic` page. So, users can view description of each song.