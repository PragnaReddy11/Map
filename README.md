## Steps to setup

- Clone the repo : `git clone https://github.com/VaithiSniper/pehchan.git`
- `cd` into the directory, and install packages with `npm i`
- Copy this file into your `public` folder : [glb files](https://drive.google.com/drive/folders/1nAkVwnHdj8YxGgsEiHLi9Ee7TtipRKHi?usp=share_link)
- Prototype Drive Link - https://drive.google.com/drive/u/0/folders/1kPBJrRqKwjbT0JGQ4iwtXG9tJIURQkzk

Description - We put forth the ICC Meta League model, which has the potential to completely change the fintech industries. The user will first log in using the "Arcana" authenticated system, which will take him to the NFTs Market Place, where he can purchase players' NFTs. In order to create an equal user interaction with women's cricket, we decided to have a 2:1 man to woman NFT ratio and set the maximum number of NFTs at 3. We created the ICC Bet DEN platform, where users can bet on their NFTs during live matches that are currently taking place while also participating in leagues. Additionally, ICC Bet DEN offers ball-to-ball predictions, where the user with the most accurate wager wins league tokens. The token can be used in a variety of ways, including cashing out with NUIM payment services, purchasing goods from ICC, and collaborating with nearby partner stores across platforms. We created the ICCC, a chatroom platform where users can specify their geographic region and other users within that region can communicate and play league games. The user can use their token to exchange goods with registered shops near them that are visible on a map. The ICCC will be integrated with ICC TV so that groups of spectators can view and discuss live matches. The local coordinates and details of the people with whom the user can interact will be available in cross-platform interaction. The ICC Meta League's most intriguing move is to rent and lease players, which will control the flow of NFTs and improve the quality of the content.

## Server

- Start the development server using : `npm run dev`

## Things to note

- We will be using the `develop` and `main` branches. The `main` branch will contain the latest stable code and the `develop` will be used for development/staging.
- **ALWAYS** start from the `develop` branch. For every new feature, make a new branch and checkout to it with `git checkout -b <branch-name>`. Make sure the branch name is verbose and indicates the feature being implemented.
- Once development is done and tested in your branch, push the branch to the remote with `git push origin <branch-name>`.
- After pushing the branch, open a PR to `develop` and tag @VaithiSniper to review.
- Follow-up and fix PR-comments if any.
- Once satisfactory, PR will be merged to `develop`.
- After a set of features are implemented and given `develop` is stable, it will be merged to `main` and must be subsequently **tested**.
