# Card Ponzi — Degen Pack Vault

Static landing page: holders of $MOONPK claim card packs and rip them open.

Zero build step. Deploy on Vercel with Application Preset "Other" and root directory `./`.

Visuals and claim flow only — wallet connect, balance check and pack rolls are
simulated in `index.html`. Swap the `claim` handler for a real Solana wallet
adapter and move the pull logic server-side before using this for real drops.
