# easy discord api
Made with ❤️ by 𝕯𝕽𝕬𝕲𝕺𝕹𝕳𝖀𝕹𝕿𝕰𝕽™®-𝔪𝔠𝔷𝔤𝔬𝔡𝔭𝔦𝔤𝔤𝔶ᴰᵉᵛ#4992
# Examples
```js
//require the package
const dapi = require("easy-discord-api")

//get's a discord user's info
dapi.duserinfo("your_bot_token_here", "user_Id").then(res => console.log(res))

//get a server member's info
dapi.dsmbinfo("your_bot_token_here", "guild_id", "member_id").then(res => console.log(res))

//get a guild's info
dapi.dguildinfo("your_bot_token", "guild_id").then(res => console.log(res))
```
[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNDIuMDIiIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAxNDIuMDIgMzUiPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9IjAiIHk9IjAiIHdpZHRoPSI3OC4wNiIgaGVpZ2h0PSIzNSIgZmlsbD0iIzMxQzRGMyIvPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9Ijc2LjA2IiB5PSIwIiB3aWR0aD0iNjUuOTYwMDAwMDAwMDAwMDEiIGhlaWdodD0iMzUiIGZpbGw9IiNFMjA4MDgiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTUuNzggMjJMMTQuMzEgMjJMMTQuMzEgMTMuNDdMMTUuNzggMTMuNDdMMTUuNzggMjJaTTIyLjA3IDIyTDIwLjU5IDIyTDIwLjU5IDEzLjQ3TDIyLjA3IDEzLjQ3TDI1Ljg5IDE5LjU0TDI1Ljg5IDEzLjQ3TDI3LjM2IDEzLjQ3TDI3LjM2IDIyTDI1Ljg4IDIyTDIyLjA3IDE1Ljk1TDIyLjA3IDIyWk0zNC40MCAyMkwzMS4zNCAxMy40N0wzMi45NiAxMy40N0wzNS4xMSAyMC4xNEwzNy4yNyAxMy40N0wzOC45MCAxMy40N0wzNS44MyAyMkwzNC40MCAyMlpNNDQuNDIgMjJMNDIuOTQgMjJMNDIuOTQgMTMuNDdMNDQuNDIgMTMuNDdMNDQuNDIgMjJaTTUwLjkxIDE0LjY2TDQ4LjI3IDE0LjY2TDQ4LjI3IDEzLjQ3TDU1LjA0IDEzLjQ3TDU1LjA0IDE0LjY2TDUyLjM4IDE0LjY2TDUyLjM4IDIyTDUwLjkxIDIyTDUwLjkxIDE0LjY2Wk02NC4zNyAyMkw1OC44MCAyMkw1OC44MCAxMy40N0w2NC4zMyAxMy40N0w2NC4zMyAxNC42Nkw2MC4yOCAxNC42Nkw2MC4yOCAxNy4wMkw2My43OCAxNy4wMkw2My43OCAxOC4xOUw2MC4yOCAxOC4xOUw2MC4yOCAyMC44Mkw2NC4zNyAyMC44Mkw2NC4zNyAyMloiIGZpbGw9IiNGRkZGRkYiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNOTIuNTggMjJMOTAuMjUgMjJMOTAuMjUgMTMuNjBMOTIuMjAgMTMuNjBMOTUuOTEgMTguMDdMOTUuOTEgMTMuNjBMOTguMjQgMTMuNjBMOTguMjQgMjJMOTYuMjkgMjJMOTIuNTggMTcuNTJMOTIuNTggMjJaTTEwMi45NyAxNy44MEwxMDIuOTcgMTcuODBRMTAyLjk3IDE2LjU1IDEwMy41OCAxNS41NVExMDQuMTggMTQuNTYgMTA1LjI0IDE0LjAwUTEwNi4zMSAxMy40MyAxMDcuNjQgMTMuNDNMMTA3LjY0IDEzLjQzUTEwOC45NyAxMy40MyAxMTAuMDMgMTQuMDBRMTExLjEwIDE0LjU2IDExMS43MCAxNS41NVExMTIuMzEgMTYuNTUgMTEyLjMxIDE3LjgwTDExMi4zMSAxNy44MFExMTIuMzEgMTkuMDUgMTExLjcwIDIwLjA0UTExMS4xMCAyMS4wNCAxMTAuMDMgMjEuNjBRMTA4Ljk3IDIyLjE3IDEwNy42NCAyMi4xN0wxMDcuNjQgMjIuMTdRMTA2LjMxIDIyLjE3IDEwNS4yNCAyMS42MFExMDQuMTggMjEuMDQgMTAzLjU4IDIwLjA0UTEwMi45NyAxOS4wNSAxMDIuOTcgMTcuODBaTTEwNS4zNyAxNy44MEwxMDUuMzcgMTcuODBRMTA1LjM3IDE4LjUxIDEwNS42NyAxOS4wNVExMDUuOTcgMTkuNjAgMTA2LjQ5IDE5LjkwUTEwNy4wMSAyMC4yMCAxMDcuNjQgMjAuMjBMMTA3LjY0IDIwLjIwUTEwOC4yOCAyMC4yMCAxMDguNzkgMTkuOTBRMTA5LjMxIDE5LjYwIDEwOS42MSAxOS4wNVExMDkuOTEgMTguNTEgMTA5LjkxIDE3LjgwTDEwOS45MSAxNy44MFExMDkuOTEgMTcuMDkgMTA5LjYxIDE2LjU0UTEwOS4zMSAxNiAxMDguNzkgMTUuNzBRMTA4LjI4IDE1LjQwIDEwNy42NCAxNS40MEwxMDcuNjQgMTUuNDBRMTA3LjAwIDE1LjQwIDEwNi40OSAxNS43MFExMDUuOTcgMTYgMTA1LjY3IDE2LjU0UTEwNS4zNyAxNy4wOSAxMDUuMzcgMTcuODBaTTExOS4xMiAyMkwxMTYuMzkgMTMuNjBMMTE4Ljg0IDEzLjYwTDEyMC41MyAxOC45NkwxMjIuMzAgMTMuNjBMMTI0LjQ5IDEzLjYwTDEyNi4xOCAxOS4wMUwxMjcuOTUgMTMuNjBMMTMwLjIxIDEzLjYwTDEyNy40OSAyMkwxMjQuOTUgMjJMMTIzLjM0IDE2Ljg5TDEyMS42NiAyMkwxMTkuMTIgMjJaIiBmaWxsPSIjRkZGRkZGIiB4PSI4OS4wNiIvPjwvc3ZnPg==)](https://dsc.gg/bot-manager)
