# $puppr staking

`npm install`
`npm start`


Needs some love.
 

src/index.html and src/connect.js are the only files in this dir that are used for the app. So, you could pull those two files out and drop them on a https server to run the app. No need horse around with 11ty and all the modules. 


- connection issues with metamask: does not stay connected. a switching of accounts in metamask does cause the app to load.
- would be nice to have app update upon succenssful stake, and unstake actions


v2.html and v2.js are copies of the above two files where i'm working on skinning. using tailwind css library


the contract is in /contracts/PupperToken.sol for reference

deployed. see here: https://bscscan.com/token/0x845b705996F4235E7E0b792d57D4bC452BA6f748
