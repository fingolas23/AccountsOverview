# AccountsOverview
An overview over (verified media) accounts in the Fediverse

The Fediverse is a network of software connected by the protocol ActivityPub and Mastodon was for a long time the most well known of them. When Elon Musk bought Twitter in 2022, many people left the network for Mastodon, some media outlets followed and created accounts to spread their content. But many people have left since then the reasons are diverse. Many headed to Bluesky, others to Threads and not so few are still active on X. 

All the while the Fediverse grew and more and more networks were connected via ActivityPub, which also means, that more and more media accounts are accessible from Mastodon & Co. even if their from someqhere else. Because discovering them is not always so easy, lists were created to help everyone finding them. This ones started as one with all verified media accounts on Mastodon, but it now contains verified accounts from Flipboard, Threads, Bluesky & more, that can be followed from Mastodon etc. 

This repository contains the code for the website – hosted on [fingolas.eu](https://fingolas.eu/fediverse/overview.html) – making the list accessible and searchable. The data itself is collected via API-requests from multiple accounts on Mastodon and processed in Google Sheets. The code here is only for the output via [DataTables](https://datatables.net/).