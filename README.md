# DirtyBit

---

DirtyBit is a BitTorrent client written in Rust.

DirtyBit is capable of parsing 
.torrent files and downloading files from a peer. 


## Make It Your Own

To use DirtyBit, your system must have [Rust](https://www.rust-lang.org/tools/install) installed. 

-  Clone the repository:
```sh
git clone https://github.com/V3D4NTH/DirtyBit
```

- Switch to the directory:
```sh
cd DirtyBit
```

- Run `./your_bittorrent.sh` to run your program, which is implemented in
   `src/main.rs`. This command compiles the Rust project, so it might be slow
   the first time you run it. Subsequent runs will be fast.

- To download files:
- 
  `./your_bittorrent.sh download -o <the path you want it to be downloaded to> <torrent file>`

- Output:

  `Downloaded sample.torrent to /tmp/test.txt.`
  

