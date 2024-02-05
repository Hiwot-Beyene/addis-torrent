# Addis-Torrent
## 4th Year Software Engineering Students 
## Addis Ababa University @2024
### Instructor: Wendimagegn Desta
### Course: Distributed System

| Name             | Roll Number  | Section |
| ---------------- | ------------ | ------- |
| Eden Asamere     | UGR/7759/13  | 2       |
| Sitra Mohammed   | UGR/0106/13  | 1       |
| Hiwot Beyene     | UGR/3774/13  | 2       |
| Yohannes Habtamu | UGR/3616/13  | 2       |
| Dawit Zeleke     | UGR/7912/13  | 2       |


### How to Use it?
## Install

Go is required

1. Library: 
     * `go get -d github.com/Hiwot-Beyene/addis-torrent/torrent`
     * `go install github.com/Hiwot-Beyene/addis-torrent/torrent@latest`

4. Client: 
     * `go get -d github.com/Hiwot-Beyene/addis-torrent/cmd/addis-download`
     * `go install github.com/Hiwot-Beyene/addis-torrent/cmd/addis-download@latest`

## Client Usage

To download a torrent from a file:

    The following command assumes that the client is installed and the executable 'addis-download' is in $PATH (because $GOPATH/bin should be in $PATH). <file> is propably a file with .torrent extension.
    $ addis-download -torrentfile <file>
    The downloaded files will be available under the current working directory.

##  What it does 

File sharing using the BitTorrent protocol.

Torrent management (creation, starting, pausing, and stopping).

Progress tracking for each torrent (completion percentage, downloaded/uploaded data).

Peer connection management (establishing and managing connections with other peers).

Piece selection algorithms for efficient downloading.

Communication with the tracker server for peer coordination.

Support for seeding (sharing files without further downloading).

Concurrency
