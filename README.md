# 🌏 anaxes.xyz

My personal site created with [HTML](https://www.w3schools.com/html/) & [TailwindCSS](https://tailwindcss.com), utilising [Lanyard](https://discord.com/invite/UrXF2cfJ7F), [GitHub](https://api.github.com) and [Twitter](https://developer.twitter.com) API.

## 📚 Credits

This personal website is heavily inspired/built off of [Audun's Personal Website](https://audun.gg).

🔗 Website: [Audun.gg](https://audun.gg)
<br/>
🔗 GitHub: [Audn](https://github.com/audn)
<br/>
🔗 Twitter: [tweetaudun](https://twitter.com/tweetaudun)

_\*Note: Audun recently updated their personal website and github repo. My personal website is built off of a previous version of their website. This repository is in no way "mine". I have just added my personality to Audun's original personal website._

## 🚀 Getting Started

To start off, please clone the repository:

```bash
git clone https://github.com/DiscordAnaxes/Anaxes.xyz
```

Next, change directory:

```bash
cd Anaxes.xyz
```

As this website uses [TypeScript](https://www.typescriptlang.org/), you will need to install it:

```bash
npm install -g typescript
```

Then, open the directory (This step is for Visual Studio Code. Please refer to your preferred IDE/Text Editor on how to open folders/directories.):

```bash
code .
```

## 🏷️ Lanyard, 🐈 GitHub API & 🐤 Twitter API

Firstly, you want to change the API endpoints in `/assets/ts/lanyard.ts`, `/assets/ts/github.ts`, & `/assets/js/twitter.ts`.

In those files please change the ending of the API endpoints:

Lanyard.js file:

```bash
https://api.lanyard.rest/v1/users/<your discord id>
```

Github.js file:

```bash
https://api.github.com/users/<your github username>
```

Twitter.js file:

Unfortunately the endpoint for the Twitter API is custom and only retrieves my Twitter account data. You'll have to use your own system on getting Twitter data.

_\*Note: To use Lanyard API you <strong><u>must</u></strong> join their [Discord Server](https://discord.com/invite/UrXF2cfJ7F) & to compile TypeScript to JavaScript: Run `tsc`_

## 🔍 Deploy on Netlify

The easiest way to deploy a website for free, is to use a provider called [Netlify](https://netlify.com).

Check out the [Netlify deployment documentation](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/) for more details.

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/DiscordAnaxes/Anaxes.xyz"><img src="https://www.netlify.com/img/deploy/button.svg"/></a>

## 👋 Conclusion

Thank you for taking your time to read this README. It would support Audun & Me greatly, if you link our respective websites in the footer area of the website (or anywhere that suits you).
