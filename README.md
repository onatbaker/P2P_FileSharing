# P2P FileSharing

For the user to experience the full-scope of the application, one must do these steps:

1) The server user should first start by booting up the `p2p_server` python script which will prompt the user
to pick one of the available `.png` files to download

2) Then, the server user should boot up the `announcer`

3) Then, the downloading user should boot up the `listener` to listen to the announcer's announcements so that it
can create a `.txt` file that contains the chunks that are to be downloaded with their respective addresses.

4) Lastly, the downloading user should boot up the `p2p_downloader` file to download all the chunks and then put them
in one piece, creating an entire `.png` file
