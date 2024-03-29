# StoryBot Privacy Policy v2

## Definitions

"I", "me", "my", etc. throughout this policy refers to the StoryBot Team.

## Non-AI Training Policy

**I will not train any text generation AI models on users' submitted stories without their express, opt-in consent**. I will also not share/sell user's stories with anyone to train an AI model on unless users explicitly opt in.

I have not trained an AI model on user stories, nor do I have any plans to. I also have not shared user stories and do not have any such plans.

This section is redundant and is implied by other parts of the policy; however, I just wanted to make this crystal clear before going any further.

## Personal data

Here is an example of some of the data my bot stores about users:

- Unique user IDs
- Servers they're registered as authors in;
- Their status in each server (active, paused, your turn, etc.);
- Servers they're banned in;
- their user configurations (modified by running `/my_config`);
- The actions each user runs for the bot, along with some metadata (such as what action, which server, timestamp, etc);
- If a user has a premium subscription, which server they are applying this to;
- Any feedback they send

Here is an example of some of the data my bot stores about each server:

- Unique guild (server) ID
- The story being written in that server, along with any previous archived stories;
- Server configuration (modified by having an admin run `/config`);
- The status of the server and the current story (when it was last updated, the current user, etc.);
- Whether the server has a subscription and if so, which user has purchased the subscription;
- Actions taken in the server, along with some metadata (such as what action, which server, timestamp, etc);
- If the bot sends a message with a button, it stores the message id along with the server the button is for. It does not store the id of the user;
- Users and their author statuses (see above).

I collect this data via interactions with the bot. StoryBoot will fetch this data whenever it is needed, but it does not store data that it does not need.

I use this data to:

- make the bot function (for example, if I can't store your settings, you can't change them);
- and fix bugs (for example, if a user reports a problem when they tried to write, I can look up their logs to help diagnose the issue);
- prevent spam (for example, if I see the number of logs spike dramatically and all of it is caused by the same few users, I can take appropriate actions);
- ensure that my bot is functioning properly (for example, if I'm in a server with you and I see a problem, I can investigate);
- investigate if a user reports that there is some serious harm being done by the bot (for example, being used to write viruses, commit phishing attacks, etc.).

**In order to see all of the personal data the bot has stored on you as a user**, you can run `/privacy request_my_data`. **In order to delete this user data**, run `/privacy delete_my_data`. Data may still be stored in a backup, but this will be deleted relatively soon afterward. Some data, such as server bans, cannot be deleted by the affected user.

**In order to delete all of the data the bot has stored about a server**, simply kick it from the server. Again, regular backups are made, but the data will not be readily accessible and will be removed when the older backups are deleted.

I will store your personal data only as long as I need to and will delete it as soon as it is not necessary.

I will not share your personal data outside of the StoryBot Team. Only members of the StoryBot Team will have access to this data. The only exceptions (see below) are requests from Discord or requirements from lawful authorities. In addition, if you explicitly opt-in to the sharing of personal data, this data might be shared. Finally, if I in good faith believe that there is serious need to, I may disclose this information (for example, if a server member reveals that some people are planning something bad using StoryBot).

## Third-party data

I am not affiliated with or responsible for any content (including links) posted on StoryBot.

## Aggregated data

StoryBot also collects and stores a aggregated data (for example, how many servers StoryBot is in, how many are active, and how many users are paused at a given time, etc.). The __aggregated, anonymized__ data I collect can be stored and shared for any reason, including:

1. improving the bot (for example, by seeing if certain actions are going unused and can thus be deprioritized);
2. sharing it with friends who are good at crunching numbers (for example, to estimate how soon I'll need a bigger hard drive);
3. for fun. For example, I can make some of the statistics public, like how I show the number of servers StoryBot is in.

To clarify, only aggregated, anonymized data will be shared. Personal data (like individual stories, if a specific user user is active in StoryBot, etc.) will not be shared unless the user explicitly opts into this or unless required by a government, Discord, etc. - see the next section for more on that.

## Other stuff

I access data thru Discord's API. I collect this data locally and store it on a local database. I will retain this data as long as it is needed and will delete it when it is no longer required or when the relevant user requests it.

Per Discord's terms and conditions, I will:

1. comply with all applicable laws and regulations;
2. not infringe or violate any third-party rights (including intellectual or other proprietary rights or rights of privacy or publicity);
3. not access or use the APIs in a manner that is deceptive, unethical, false, misleading, or encourages or promotes illegal activity or infringement or violation of third-party rights; and 
4. not violate any other terms or policies with Discord.

As of now, I do not share this data with third parties. In the future, I will not share API Data with any third party, except in the following circumstances, subject to compliance with the Terms and applicable laws and regulations:

1. with a Service Provider;
2. to the extent required under applicable laws or regulations; and 
3. when a user of your Application expressly directs you to share their API Data with the third party (and I will provide Discord proof thereof upon request).

Except to the extent I am required to retain API Data under applicable laws or regulations, I will

1. promptly update the API Data upon request from us or the applicable user, and
2. promptly delete the API Data when:
  a. retaining it is no longer necessary for your Application’s stated (and approved through App Review, as applicable) functionality that is permitted under the Terms;
  b. you stop operating your Application (whether on my own, due to an enforcement action by Discord, or otherwise);
  c. Discord requests I delete it;
  d. the applicable user requests I delete it; or
  e. required by applicable laws or regulations.

## Updates to this policy

If I update this policy, I will send a message in my public StoryBot server. I will also update this Github repository and publish a new release.

## Please contact me!

If you have any questions, you can join [my Discord](https://discord.gg/a28VUkyrxp) and I will be happy to answer them.

In order to keep up-to-date with changes in this privacy policy, watch this repository. My current privacy policy will be listed in the releases of this repository.
