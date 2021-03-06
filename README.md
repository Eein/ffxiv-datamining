# XIV-Datamining

This repository is to serve as a place to share data mining information related to Final Fantasy XIV. All findings and knowledge that each member discovers will be provided here for all in the FFXIV Community to read, learn and use.

Huge thanks to the community team members involved:

- [Ioncannon](https://www.reddit.com/user/Ioncannon) from [FFXIV Explorer](http://ffxivexplorer.fragmenterworks.com)
- [Clorifex](https://www.reddit.com/user/Clorifex) from [GarlandTools](http://www.garlandtools.org/db/)
- [Hezkezl](https://www.reddit.com/user/Hezkezl) for being awesome

## Updating CSV files:

- Download and open **SaintCoinach.cmd**
- Run: `rawexd`
- Copy all the contents in the folder: `<date>/rawexd/**` to the `/csv` folder
- Push a PR

The idea is to maintain an easy diffing view of what has changed during a patch

It would also be very useful to keep a history of `ex.json` files from SaintCoinach for each patch as the Korean and Chinese versions are on different patches than the Official live client.


## Helping out

Getting started in datamining is quite easy. If you enjoy digging around CSV database files then you've come to the right place! The best place to start would be:

- Download this repository and start looking at the files in the `/csv` folder
- Download **SaintCoinach** and use either the `SaintCoinach.Cmd` or `Godbert` tools.
	- Saint provides releases: https://github.com/ufx/SaintCoinach/releases

If you find a connection between files or an identification of data, throw up an issue on the repository and it will be sorted :)

- Connection between files could be an number in 1 column that matches the numbers in another column or even another file
- Identification of data could be values in a column that have a meaning and a pattern can be observed (eg ClassJob ID, or Craft Level)

# The tools of the trade

### Saint Coinach

- Written by: Clorifex and Rogueadyn
- GitHub: https://github.com/ufx/SaintCoinach
- Downloads: https://github.com/ufx/SaintCoinach/releases
	- SaintCoinach.Cmd is a tool to rip data (csv, music, icons, maps, etc)
	- Godbert is a *viewer* tool to browse data.

A great tool showing really impressive results, it will allow you to view and export a lot of data. The source is all open for your luxery.


---


**Other cool projects**

- REST API for FFXIV via XIVDB: https://github.com/xivdb/api
- (PHP) Lodestone Parser: https://github.com/viion/lodestone-php
- (PHP CLI) Libra exporter: https://github.com/viion/libra-php
- (PHP CLI) Lodestone Icon Ripper: https://github.com/viion/lodestone-icons
- (PHP CLI) SaintCoinach CSV Parser: https://github.com/viion/saint-csv-parser
- (C#) Memory Reader: https://github.com/Icehunter/sharlayan
- (NodeJS) Dead Lodestone Parser: https://github.com/viion/lodestone-nodejs


