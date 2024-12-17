# iscord-Exclusive-Console-JS

⚠️ **Note**: I'm not affiliated with Discord and do not encourage using any of these scripts. Use everything here at your own risk. This is meant for **educational purposes** only and using these codeblocks may result in your account being disabled/terminated.

# Inner workings of Discord

**Disclaimer**: The information provided in this section is obtained through reverse engineering and NOT verified for it's accuracy. Therefore it might be outdated as well.

**My Exclusive Console JS For Discord**

## Scripts

- `Friend Invite Link`: Generate a friend invite link
- `Client Side Nitro JavaScript`: Spoof the client and enable client side Discord Nitro
<header>
  
# Friend Invite Link

<details>
  <summary>Expand</summary>
  
  ```js
webpackChunkdiscord_app.push([[[Math.random()]],{},q=>Object.values(q.c).find(e=>e.exports?.Z?.createFriendInvite).exports.Z.createFriendInvite().then(console.log)])
  ```
</details>

  # Client Side Nitro JavaScript

<details>
  <summary>Expand</summary>
  
  ```js
webpackChunkdiscord_app.push([[[Math.random()]],{},q=>Object.values(q.c).find(e=>e.exports?.default?.getCurrentUser).exports.default.getCurrentUser().premiumType=2])
  ```
</details>

</header>
