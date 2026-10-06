# Nova Command Center

Voice front-end for Nova (the AI chief of staff in the private `nova-hq` repo).

- Tap the star, speak in Hindi/Hinglish/English. Simple questions ("status", "approvals")
  are answered instantly from HQ files; real tasks become a `nova-task/<id>` pull request,
  which wakes the "Nova inbox" cloud routine. Nova's spoken reply is read out loud.
- Live team graph, communications feed, one-tap approvals, and spoken alerts.

This repo holds only the static page. No data or keys live here: each device connects with
its own fine-grained GitHub token (Contents + Pull requests on `nova-hq` only), stored in
that browser's localStorage.
