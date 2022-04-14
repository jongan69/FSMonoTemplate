# Full Stack Web3 Monorepo

Using Expo React Native &  Nextjs API + Moralis + WalletConnect

Mobile App Repo: https://github.com/jongan69/FSexpoApp

Nextjs App Repo: https://github.com/jongan69/FSnextApp/

# Goals

Nextjs offer a full frontend and backend structure that is extremely powerful...in webapps.

In React Native Expo, we get similar React Functionality...in Mobile Apps.

The two keep trying to be pair together whether it be Next Auth for mobile sessions or Expo Nextjs adapter
A Nextjs implementation to accept...React Native componenets?
Idk there's work to be done.

The goal is simple: Create a single monorepo for Mobile and Web in a fullstack manor using a Single API Backend amoung several
Applications.
With the introduction of Web3, Authentication is now almost entirely client side, we just need an address and the blockchain takes
care of the rest. I want to make other apps but a fullstack monorepo for Web3 should exist, React is everywhere and yet no ones using it to its full potential. The repos are open souce, Im around, PM me for Pull requests so we can speed up rebuilding the internet. 

# Planned Structure / Roadmap

Mobile app uses Expo for React front end 
Web app uses Nextjs for Full stack
Nextjs API provides and collects data of the Mobile app via wallet authenticated API calls

Mobile App access will only be allowed via an Authenticated NFT, No NFT, No dynamic data
Demo functionality will be similar to an unauthenticated User (Not signed in with wallet)
Webapp just provides minting and reading of the said provided NFT.
