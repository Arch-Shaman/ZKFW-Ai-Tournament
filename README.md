# Zero-K / Future Wars AI Tournament submissions

This repo serves as the submission base for the Winter AI War. To enter, create a PR creating a folder with your IGN (In Game Name) using the files in the "base submission" folder found here. Alternatively, you may contact me via discord (hellaratsastaja) and submit files that way.

# Rules of Engagement

1. You may have up to 3 AI configs for your team. Specify your setup using a teaminfo.md created in your submission folder.
2. Please keep your AI testing games public and accept any AI trainers in your room. Designate your test games as "[T] AI Testing". This isn't strictly required, but the goal is to have information symmetry.
3. You may challenge other trainers to an AI Duel during testing or peak into their games for intel gathering. You may also metagame through the github files here.
4. You may not create separate configurations per match!
5. There will be exhibition matches (unranked) every 2 weeks. Please have your files ready by then. PRs will be approved as they can be.
6. Your submission may not use LOS Cheats.

7. You will be ranked in the finals based on your wins and losses:

        Win Against another AI Team: +2pts ✔️
        Win Against FWBrutal/Brutal AI: +1pt ✔️
        Loss: -1 pt. ❌
        Draw (match goes beyond 45:00) : 0pts for both teams. 🏳️

8. Each team will fight in 2 matches Round Robbin style. In addition, each team will fight against Brutal AI and FWBrutal twice.
----

# Getting Started
1. Copy the base files of the game of your choice to `Zero-K/AI/Skirmish`. If you're playing future wars, create two (if you do not have FWBrutal already). You should have a folder like this: `Zero-K/AI/Skirmish/MyAIName/stable`
2. Rename the folder to whatever you'd like. I don't think spaces work, but whatever?
3. Update the AIInfo.lua's `shortName` field to match the folder name.
4. Create `devmode` as a text file in your Zero-K folder.
5. Disable `Simplified AI List` in the Zero-K Lobby Settings under the `Developer` tab.
6. You're ready to go! Everything you'll probably want to change is in `/config`.

# Submitting work
You'll need to create a PR here or give me the files via discord. Every 2 weeks, we will have an exhibition match, be sure you have your files up to date as this will provide you with good testing to see where you stand!

Deadline for submissions: December 30th! Have fun. Feel free to join #Modding or #AI to collaborate and ask questions.

Good luck, have fun.
