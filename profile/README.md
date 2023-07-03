## Hello there 👋

Sweep (https://github.com/sweepai/sweep) is a Github assistant the helps you fix small bugs and implement small features. You write tickets and Sweep fixes them so you can focus on the challenging engineering problems.

For some examples of tickets made by Sweep, check out https://github.com/edreisMD/plugnplai/issues/140, https://github.com/edreisMD/plugnplai/issues/122 and [🎟️ Example Sweep Tickets](https://docs.sweep.dev/examples) for more.

## Getting started


### 🖥️ Sweep Chat
Sweep Chat allows you to interact with Sweep locally and will sync with GitHub. You can plan out your changes with Sweep, and then Sweep can create a pull request for you. 

1. Install [Sweep GitHub app](https://github.com/apps/sweep-ai) to desired repos

2. Run `pip install sweepai && sweep`

3. This should spin up a GitHub auth flow in your browser. Copy-paste the 🔵 blue 8-digit code from your terminal into the page. Then wait a few seconds and it should spin up Sweep Chat. You should only need to do the auth once.

4. Pick a repo from the dropdown at the top (the Github app must be installed on this repo). Then start chatting with Sweep Chat. Relevant searched files will show up on the right. Sweep Chat can make PRs if you ask it to create a PR. 
<img src="https://github.com/sweepai/sweep/blob/856ff66c2dbeaf39afbf6d8c49a620dfa70271fb/.assets/gradio-screenshot.png">

💡 You can force dark mode by going to http://127.0.0.1:7861/?__theme=dark.

#### From Source
If you want the nightly build and or if the latest build has issues.

1. `git clone https://github.com/sweepai/sweep && poetry install`
2. `python sweepai/app/cli.py`

### ✨ Sweep Github App
Setting up Sweep is as simple as adding the GitHub bot to a repo, then creating an issue for the bot to address.

1. Add the [Sweep GitHub app](https://github.com/apps/sweep-ai) to desired repos
2. Create new issue in repo, like "Sweep: Write tests"
3. "👀" means it is taking a look, and it will generate the desired code
4. "🚀" means the bot has finished its job and created a PR

For more detailed docs, see [🚀 Quickstart](https://docs.sweep.dev/start).

## Privacy

Sweep does not store your code., but instead embeds your code and stores them in a vector DB with reference to the file names and line numbers, but your code is not stored as plaintext. For our full privacy policy, check [🔒 Privacy Policy](https://docs.sweep.dev/privacy-policy).

## Get connected

Connect with our community at https://discord.gg/sweep-ai. Don't hesitate to reach out to us if something breaks or if you have fresh ideas for Sweep. 💬👥

Stay updated with Sweep at:

🐦 https://twitter.com/sweep__ai

🔗 https://sweep.dev/

✉️ team@sweep.dev

We aim to make your development experience smoother and more efficient. Give Sweep a try today and let the magic happen! ✨🤖
