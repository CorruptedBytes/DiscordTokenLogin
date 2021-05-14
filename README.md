# DiscordTokenLogin
If you paste this script into the console, you can log in with a Discord token.

```javascript
function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 2500);
}
```
