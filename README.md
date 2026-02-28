Little Vault – A Digital Scrapbook with Time-Locked Memories

Little Vault is a secure and emotionally designed digital scrapbook where users can store multiple photos and messages inside private memory collections and unlock them at meaningful moments in the future.

Unlike traditional storage apps, Little Vault transforms memories into a romantic scrapbook experience. Users can create a “vault,” add multiple photo-message entries, set unlock dates, and optionally protect them with a secret password. When the unlock date arrives, the memory opens with an animated scrapbook interface, creating an emotional storytelling experience.
<img width="1920" height="1080" alt="Screenshot 2026-02-28 080334" src="https://github.com/user-attachments/assets/52f14b58-ff74-42e0-a1de-fb5db3023884" />
<img width="1920" height="1080" alt="Screenshot 2026-02-28 080351" src="https://github.com/user-attachments/assets/fc3e8c4b-e526-46b4-8ed5-53b77181de38" />


https://github.com/user-attachments/assets/47086f3b-6285-4ca2-959f-8d158a070cff
┌────────────────────┐
            │     User Opens     │
            │     Little Vault   │
            └─────────┬──────────┘
                      │
                      ▼
            ┌────────────────────┐
            │  Login / Sign Up   │
            └─────────┬──────────┘
                      │
                      ▼
            ┌────────────────────┐
            │   Dashboard Page   │
            │  (View Memories)   │
            └───────┬─────┬──────┘
                    │     │
        ┌───────────┘     └────────────┐
        ▼                               ▼
┌──────────────────┐          ┌──────────────────┐
│  Create Memory   │          │   Open Memory    │
└─────────┬────────┘          └─────────┬────────┘
          │                               │
          ▼                               ▼
┌──────────────────┐          ┌──────────────────┐
│ Add Multiple     │          │ Check Unlock Date│
│ Photos & Messages│          └─────────┬────────┘
└─────────┬────────┘                    │
          │                              ▼
          ▼                    ┌──────────────────┐
┌──────────────────┐           │ If Locked → Show │
│ Upload Images to │           │ Lock Message     │
│   Cloudinary     │           └─────────┬────────┘
└─────────┬────────┘                     │
          │                               ▼
          ▼                     ┌──────────────────┐
┌──────────────────┐            │ If Unlocked →    │
│ Save Data in     │            │ Show Scrapbook   │
│ Firestore        │            │ View             │
└─────────┬────────┘            └──────────────────┘
          │
          ▼
┌──────────────────┐
│ Redirect to      │
│ Dashboard        │
└──────────────────┘
