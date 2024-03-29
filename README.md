# MintMatch

[Join Waitlist!](https://mintmatch-website.vercel.app/)

## Intro
This is a DevLog for A social app project for NFTs collectors built with React Native.  
Looking forward to get any suggestion!

[Legacy Version](https://www.canva.com/design/DAFvV3fdaGo/a77okZsEnezx90ybP_ZwJg/view?utm_content=DAFvV3fdaGo&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

## Tech Stack
- React Native
- JavaScript 
- Python
- Solidity
- Google Firebase
- Amazon RDS (MySQL)

## Web3 Provider
- [Alchemy](https://www.alchemy.com/)
- MetaMask
- [xmtp](https://xmtp.org/)
- Infura
- Pinata IPFS

## Chain
- Eth Mainnet
- Eth Sepolia
- Polygon Mumbai

## Progess

### Finished
- Registered and Connect Wallet
  - Connect MetaMask ✅
  - Register pages and flow ✅
  - Upload profile to server ✅
- Card
  - Swiping ✅
  - Content ✅
### In Progress
- Chat
  - [xmtp](https://xmtp.org/) ⚒️
  - Chat  ⚒️
  - Trade NFTs  ⚒️
  - Allow users to add new contact ⚒️
  - Search by user name ⚒️
  - Swap NFTs ⚒️
  - Search and send arbitrary NFTs ⚒️
- Utils
  - Scan the QRcode to add a new contact ⚒️
  - Generate the QRcode for the wallet address ⚒️

### TODO
- Matching Algorithm
- Chat 
- Trade NFTs 
- Share NFTs 
- Mint NFTs 
- Loyalty Systems
- Activities & Events
- Market place

## Dev Logs
#### Jan 15 2024
Progress:
  - Enable users to use NFTs on different chains to build up their profile
  - Enable users to share owned NFTs on different chains in the chatroom


https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/dce95f3f-b703-493c-be9f-e73bea3abb7e


https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/7cf43a45-30db-4698-bcda-a2e14c826387




#### Jan 15 2024
Progress:
  - Replace inApp trading NFT with only one single transaction (remove Oracle)
  - Fix bugs for wallet connecting and chain switching
  - Match users and create new chat room

TODO:
  - Share arbitrary NFTs in the chat room



#### Jan 2 2024
Progress:
  - Complete inApp trading NFT

TODO:
  - Catch bugs and fix MetaMask sdk disconnect issue (Automatically disconnected after MetaMask wallet app is locked)



https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/3ae002fd-f9e0-4460-a02f-3e5c3717b825





#### Jan 1 2024
Progress:
  - Ask for asset transfer approval from the user
  - Update approval status to the database
  - Testing transaction smart contract, and complete token transfer and NFT transfer. (from remix)

<img src="https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/3ede6f5a-9eca-4502-9ae1-442e62593ff4" width="300" height="650">  

![Screenshot 2024-01-01 at 8 46 36 PM](https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/5c25e770-2494-4fa2-97c9-e9a199ffa122)

    


#### Nov 26 2023
Progress:
  - The first user that accepts the purpose will sign the purpose information upload it to IPFS and then store it in the database
  - Check if the purpose is registered
  - Validate function which checks if the signature is legit and all the transaction information is correct and is called by the correct user.


#### Nov 25 2023
Progress:
  - Switch Chain
  - Provider for read-only contract call (Metamask provider frequently needed the user to unlock the app to use eth_call, which is annoying)
  - Check if the seller owns the NFT & check if the buyer has enough erc-20 token balance 

#### Nov 21 2023
Progress:
  - Message block for displaying purpose



https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/5e0ecda6-3415-4cd8-8da8-e50a69237acd


#### Nov 20 2023
Progress:
  - View for sending Purpose
  - Adding WebView for NFT Information
  - Token selector

TODO:
  - Find a suitable token price API to show price preview (to USD) when typing the token amount


https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/03b62fe3-47af-495d-ad55-b9cfcfaa133b


#### Nov 17 2023
Progress:
  - Enable sending messages with NFT
  - Reply NFT with text
  - Display ownership of the NFT quoted in chats
  - Testing smart contract transaction


https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/28f0db89-184f-4bd2-aa0a-5546c00a6046





#### Nov 13 2023
Progress:
  - Migrated to tab navigation
  - Adjusted keyboradAvoidingView with safeAreaProvider
  - Fix bugs for chat view when users switch wallet address
  - Add profile card view in the chatroom



https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/12b3479c-7da9-46a3-bd01-c7d6d61a46c3



#### Nov 11 2023
Progress:
  - Chat room layout
  - Realtime message update
  - Send text message

https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/58c4c248-1f52-4dc6-8cbb-bb94ec0ab9d7



#### Nov 8 2023
Progress:
  - Dynamic source for NFT image/video 
  - Adjusted media source request timeout to improve performance
  - List all xmtp conversations and filter unregistered users
  - Push the latest conversation to the top on received new message
  - Fix bug for card swiping

TODO:
  - Add preview message and received time
  - local cache


https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/da46edb5-baf5-4022-ba9b-993debb43f6d




#### Nov 26 2023
Progress:
  - Fixing bugs in profile editing
  - Migrating scroll view to flash list
  - Preparing for xmtp implmentation

#### Nov 20 2023
Progress:
  - Finished Profile edit
  - Integrated Jotai for state management


<img src="https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/9c688fc4-90b0-4a93-acb4-be15eadfe874" width="300" height="650">
<img src="https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/6961778a-0516-4304-abbf-b16df9b6fa2a" width="300" height="650">
<img src="https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/a6565924-8d93-4790-a4a7-c44e41ac8c48" width="300" height="650">


#### Nov 15 2023
Progress:
  - Redesign Card layout
  - Add profile image to property
  - Add user ID to property
<img src="https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/a1e06dfc-4051-4dee-b371-353419d126ba" width="300" height="650">



#### Nov 14 2023
Fix:
  - Integrated EtherJS with more functionality
  - Track user Switch between Wallet address


#### Nov 11 2023
Progress:  



https://github.com/WilliamYWY/MintMatch_devlogs/assets/92711171/722a45a1-042b-441a-ab6a-88dc2dfbf951

  - Complete the whole registration process
  - Upload profile to Python server and store in Firebase
  - Fetch all card stack (other users' profile from server) and render into a card stack view
  - Swipe animation

To Fix:
  - Swipe animation warning ⚠️ (Not urgent)
  - NFT display when bad source (Urgent)

#### Nov 10 2023

Fixed Bugs:
  - Deal with mislabeled image/animation URLs from data provider
  - Optimized UX with pagination 


#### Nov 6 2023
<a href="https://drive.google.com/file/d/1acUnl2OTCq8Pd99IOwKC2oM751o_Nwhi/view?usp=drive_link" target="_blank">Full Video</a>

https://github.com/WilliamYWY/MintMatch/assets/92711171/f6108a97-14e7-4921-90cf-08f0dad75e87





