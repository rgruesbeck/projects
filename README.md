## Web
### `multibook`
Simple app for Jazz lead sheets, loading images from the Archive, and index from IPFS.
Plans for hosting/pinning images from browsers when IPFS browser nodes have more support...

`React, Archive.org, IPFS`

<div align="center">
		<br/>
			<a href="http://multibook.rocks/">
				<img src="https://github.com/rgruesbeck/projects/blob/master/media/mb1.gif" alt="multibook" width="80%">
			</a>
		<br/>
		<br/>
</div>

[link](http://multibook.rocks/)

[source](https://github.com/rgruesbeck/multibook)

### `imageHorde`
Content addressable image server.
Uploaded images are stored on disk and on IPFS.
Images are available by hash.

`Node, LevelDB, IPFS`

[source](https://github.com/rgruesbeck/imgHorde)

### `spaceblox`
Prototype webclient for space management.

`React, SVG, Leaflet`

<div align="center">
		<br/>
			<a href="">
				<img src="https://github.com/rgruesbeck/projects/blob/master/media/sb3.gif" alt="multibook" width="80%">
			</a>
		<br/>
		<br/>
</div>

### `arts council napa valley`
Website for arts non-profit with artist's profile feature.

`Ruby on Rails`

[link](https://www.artscouncilnapavalley.org/)

## CLI

### `org2invoice`
Generate html invoices from .org files containing org-clock entries.

`Node`

``
  $ org2invoice timelog.org > invoice.html
``
``
  $ pandoc invoice.html -o invoice.pdf
``

[npm](https://www.npmjs.com/package/org2invoice)
[source](https://github.com/rgruesbeck/org2invoice)

### `manual wallet`
Generate a new bitcoin address from physical coin tosses.

Keeps track of coin tosses then prints public key, private key, and mnemonic after 256 tosses.

`Bash, Libbitcoin`

[source](https://gist.github.com/rgruesbeck/d75fc0f054f42489610e6824acef5358)

### `mux`
A handy tmux wrapper.

Attach to running sessions, creat new sessions, and spin up templates by name.

`Bash, Tmux, Teamocil`

<div align="center">
		<br/>
			<a href="">
				<img src="https://github.com/rgruesbeck/projects/blob/master/media/mux.gif" alt="mux" width="80%">
			</a>
		<br/>
		<br/>
</div>

[source](https://gist.github.com/rgruesbeck/ead07be89279027bc17029d672d47c7e)

### `public record magick`
Script for creating text searchable pdfs from image files.
I wrote this script for a friend's neighborhood group who needed better access to  public records which were only available to read in the city offices. The workaround was to take digital photographs and use this script to generate pdfs with OCR making a text searchable trove of documents playing a part in the group successfully forcing a developer to build more parking space in a new residential building. 

`Bash, Imagemagick`

[source](https://github.com/rgruesbeck/publicRecordMagick)

## Containers

### `trezorfox`
Access trezor from a containerized deamon and browser.

`Docker`

[source](https://github.com/rgruesbeck/trezorfox)
