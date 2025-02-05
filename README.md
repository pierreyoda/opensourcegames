# Open Source Games

**[Dynamic HTML table](https://trilarion.github.io/opensourcegames/)** of the entries / Development **[Blog](https://trilarion.blogspot.com/search/label/osgames)** / **[Statistics](statistics.md#statistics)**

[comment]: # (start of autogenerated content, do not edit)
**[All](games/_all.md#All)** (750), **[Action](games/_action.md#action)** (138), **[Adventure](games/_adventure.md#adventure)** (18), **[Arcade](games/_arcade.md#arcade)** (27), **[Board game](games/_board-game.md#board-game)** (9), **[Card game](games/_card-game.md#card-game)** (1), **[Educational](games/_educational.md#educational)** (3), **[Framework](games/_framework.md#framework)** (61), **[Game engine](games/_game-engine.md#game-engine)** (23), **[Library](games/_library.md#library)** (22), **[Music](games/_music.md#music)** (5), **[Platform](games/_platform.md#platform)** (18), **[Puzzle](games/_puzzle.md#puzzle)** (51), **[Remake](games/_remake.md#remake)** (289), **[Role playing](games/_role-playing.md#role-playing)** (133), **[Simulation](games/_simulation.md#simulation)** (51), **[Sports](games/_sports.md#sports)** (12), **[Strategy](games/_strategy.md#strategy)** (188), **[Tool](games/_tool.md#tool)** (16), **[Visual novel](games/_visual-novel.md#visual-novel)** (4)

[comment]: # (end of autogenerated content)

A list of open source games sorted by genre. The projects are at least in beta stage with a code basis that builds
into an executable demo. The code must be under a [FOSS](https://en.wikipedia.org/wiki/FOSS) license that allows
modification and sharing by others. For each entry, relevant information is collected regarding code repositories,
download possibilities and build instructions.

Similar collections include [Open Source Clones](https://github.com/opengaming/osgameclones) of popular games;
Popular games, add-ons, maps, etc. [hosted on GitHub](https://github.com/leereilly/games); [List of open-source video games](https://en.wikipedia.org/wiki/List_of_open-source_video_games) on Wikipedia or the [LibreGameWiki](https://libregamewiki.org/Main_Page).

## Contribute

To add or modify entries, please use the [Issue tracker](https://github.com/Trilarion/opensourcegames/issues),
or fork this repository and submit a pull request.

### Adding a new entry

Checklist for a new entry

- Must be a game, a game maker, a game's tool, a framework or a library, used in games
- Must be under a FOSS license (GPL, MIT, ...) and code must be available
- Must be mature or at least in beta (with an executable demo)
- Active or inactive is irrelevant.

All entries are stored as [markdown](https://en.wikipedia.org/wiki/Markdown) text with some specific conventions.
Adding a new entry is as easy as modifying the [template](games/template.md) and adding the modified markdown file in a subdirectory of [games](games).

Description of the fields in the template. Comments start with "//".

<pre>
# {NAME} // name of the game

_{Description}_ // single description line (typically taken from about page of game)

- Home: {URL} // project main site(s) (most significant first)
- Media: {URL} // (optional) links to wikipedia and other significant mentions
- State: {XX} // one of {beta, mature} and optional "inactive since YEAR"
- Play: {URL} // (optional) link(s) to online play possibility
- Download: {URL} // (optional) link(s) to download binary (or source) releases
- Platform: {XX} // (optional) list of supported platforms {Linux, Windows, macOS, Android, ..}
- Keywords: {XX} // list of tags describing the game, first tage is the main category tag
- Code repository: {URL} // code repositories (most significant first)
- Code language: {XX} // programming language(s) used 
- Code license: {XX} // license of the code, use "Custom" with comment in () if the license is project-specific
- Code dependencies: {XX} // (optional) important third party libraries / frameworks used by the project
- Assets license: {XX} // (optional) license(s) of the assets (artwork, ..)

// whatever you want to put here

## Building

- Build system: {XX} // (optional) typically one of {CMake, Autoconf, Gradle, ..}
- Build instructions: {URL} // (optional) link(s) to build instructions offered by the project

// whatever you want to put here
</pre>

- If there are multiple links, licenses, ... separate them by comma.
- The same link can be assigned to different fields (home could also be the code repository, etc.).
- Put comments in "()" parentheses (do not put commas in comments).
- Remove lines with fields that do not apply to the project or where information is not available otherwise.
- Status active is implied/default unless the optional "inactive since" is present
- All lines starting with '- ' are considered fields.

Help: [MarkDown Help](https://help.github.com/articles/github-flavored-markdown), [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Background

I love open source projects and games and I am interested in learning more about building systems.
I see the following benefits of having this database.

- General information about open source games
- Possibility of improving build instructions on the projects side (not all projects actually have build instructions)
- Revival of abandoned games that do not build anymore
- Conversion of old repository formats like CVS to Git

## Disclaimer
 
No warranty whatsoever of the information presented herein for any purpose. There could (will) be errors in here.

## License

See [LICENSE](LICENSE) for the primary license. You are free to do whatever you want with this repository.

Just in case you are worried if you can use the content: While the WTFL license is the primary license,
this project is also multi-licensed under the following other licenses: [CC-SA-3.0](https://creativecommons.org/licenses/by-sa/3.0/), [GFDL](https://www.gnu.org/licenses/fdl-1.3.txt), [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) and the Public Domain (wherever it exists).

I hope that this does the trick. But really, just use the content.
