Here is the data my bot stores about users:
- User ID (the bot does not store usernames or discriminators);
- Servers they're registered as authors in;
- Their status in each server (active, paused, your turn, etc.);
- Servers they're banned in;
- their user configuration (modified by running `/my_config`);
- The actions each user runs for the bot, along with some metadata (such as what action, which server, timestamp, etc);
- If a user has a premium subscription, which server they are applying this to.

Here is the data my bot stores about each server:
- Guild ID (the bot does not store server names);
- The story being written in that server, along with any previous archived stories;
- Server configuration (modified by having an admin run `/config`);
- The status of the server and the current story (when it was last updated, the current user, etc.);
- Whether the server has a subscription and if so, which user has purchased the subscription;
- Actions taken in the server, along with some metadata (such as what action, which server, timestamp, etc);
- If the bot sends a message with a button, it stores the message id along with the server. It does not store the id of the user;
- Users and their statuses (see above).

I collect this data via direct interactions with the bot.

I use this data to:
1. make the bot function;
2. prevent spam;
3. ensure that my bot is functioning properly;
4. improve the bot (for example, by seeing if certain actions are going unused and can thus be deprioritized);
5. If a user reports that there is some serious harm being done by the bot (being used to write viruses, commit phishing attacks, etc.), then I will investigate,

In order to see all of the data the bot has stored on you, you can run `/privacy request_my_data`.

In order to delete this data, run `/privacy delete_my_data`. Data may still be stored in a backup, but this will be deleted relatively soon afterward. Some data, such as server bans, cannot be deleted by the affected user. In order to delete all of the data the bot has about a server, simply kick it from the server.

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

**I will not train any text generation AI models on users' submitted stories without their express, opt-in consent**. I do not have any plans to do anything of this sort, but I'm leaving this in here to clarify my position on the issue.

If you have any questions, you can join [my Discord](https://discord.gg/a28VUkyrxp) and I will be happy to answer them.

In order to keep up-to-date with changes in this privacy policy, watch this repository. My current privacy policy will be listed in the releases of this repository.
