# SkyShort
Link shortener utilizing SkyDB for link storage.

# Function
It generates a random string which it uses for the link ending and to generate a keypair. The link is then entered into SkyDB as the maximum limit of uint's (9223372036854775807) as you can't edit anything beyond that. Then, even though the link ending can regenerate a private key for anyone who's curious, the revision number has already reached its maximum capacity, so there is no way to edit it further.

# License
MIT
