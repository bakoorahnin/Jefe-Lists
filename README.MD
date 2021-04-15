Big thanks to [OISD](https://oisd.nl/), [Wally3K](https://firebog.net/), [Energized](https://github.com/EnergizedProtection/unblock) and [Sekhan](https://github.com/Sekhan/TheGreatWall) for creating these lists, without them I would not be writing these words.

The rest of this readme is a WIP for now.

All I am trying to do is compile some adblock syntax only lists with Adguards Hostlist Compiler and what you see here is:

1. Allowlist.txt - This is a compiled down list from Energized Unblock, simply removing a lot of comments and any parts that are not allowed per Adguard.
2. ticked_blocklist.txt - This is a compiled list from Wally3k of all his ticked lists at https://v.firebog.net/hosts/lists.php?type=tick checked against Energized Unblock, and removing all comments.
3. non_ticked_blocklist.txt - This is a complied list form Wall3k of all his non-ticked lists at https://v.firebog.net/hosts/lists.php?type=nocross checked against Energized Unblocked, and removing all comments.
4. oisd_blocklist.txt - I have compiled osid adp full list to remove comments, checked against Energized Unblock and I have added Sekhan's The Great Wall DoH to this list since I do not want users to use DoH on my network and bypass my DNS.

If you are unsure what list to use I generally recommend `oisd_blocklist.txt`, but feel free to try the others and see how they work for you. If you find an issue please submit a bug and PR's are welcome! I am looking for help to maybe streamline my github action.

This list is updated nightly at 1am.