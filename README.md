<img width="1911" height="945" alt="VP_2" src="https://github.com/user-attachments/assets/4648f4d2-432c-4df3-99af-ecb756da1a16" />

Vault Pact is a community-built dApp for EVE Frontier that lets you turn your Smart Storage Unit into a shared vault. Whitelist your corp mates, set up access rules, and track everything through a live transaction history pulled straight from the Sui chain.

---

Features
+ Connect your EVE Vault wallet and auto-detect your storage structures
+ Create a shared vault on any of your SSUs with one transaction
+ Whitelist players and tribes for deposit and withdraw access
+ Browse vault and owner inventory grouped by item category with icons
+ Full deposit and withdraw history with character names and timestamps
+ Analytics dashboard showing activity trends, top items, and most active users
+ Accessible Vaults tab to discover and browse vaults you have been whitelisted on
+ System notes and network node info per structure so you always know what is where
+ SUI testnet faucet shortcut built in for easy onboarding
+ *New* **Blueprint Calculator** and ingredient lookup, pulling amounts from storage counts (*web only*)

---  

V3 Update and Contract Additions:  
+ Added better contract tracking on chain for SSU ownership and deposit/withdrawal
*(before they would sorta all jumble up as deposits/withdrawals from the wallet that set the dapp up on the SSU)*  
+ Moved Blueprints and Icons over to my API
+ Added a migration feature for moving V1 vaults up to V3 - this can be found in the Extra Services panel at the bottom
+ Added better Delete Vault functions *(auto moves items back into player storage)* and a better item recovery function should anything get oddly stuck in a vault
+ Added a new Pact Tools panel for V3 vaults - Very much a work in progress, just messing around with what I can do:
  
  **Plans:** Import Blueprint jobs to a shared production board where everyone can work towards building something that pull inventory totals from the shared vault
  (I need to do more testing on this to see what the best way to flow in resources is ie. Just the shared vault or everyones vaults linked through the dapp)  

  **Bulletin:** Basic message board for planning or other conversation
  
  **Location:** Add in location data for the SSU, this is then shared and updated below in the Structure SYSTEM column and shows for every member on the vault

  All data in Pact Tools is encrypted on chain and only able to be seen/decrypted by the wallets in the member list.
  You should also be able to see the Plans and Bulletins of those SSUs from your own SSU if you have the dapp on it.
  I am trying to get it so you can join in on Plans from far and write messages but I need to do more testing. (let me know how it goes if you try it out)

+ Updated blueprints to include what assembly makes them and fixed a bunch of incorrect blueprint costs


  

  
Built on Sui testnet (Stillness)
