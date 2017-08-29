---
layout: post
title: What is OAuth?
date: 2015-01-06 13:43:31.000000000 +02:00
type: post
published: true
status: publish
categories:
- Accounts
tags: []
meta: /what-is-oauth/
---

BlueMail uses the highest privacy &amp; security authentication available for your provider.

Some providers such as Gmail and Outlook, support [OAuth](/what-is-oauth/), which means that BlueMail does not handle your login credentials at all. Instead, OAuth works by approving BlueMail as an application, and letting it access your mail, for as long as you would like.

This process involves authorization directly with your provider (who already knows your credentials: username and password) afterwards, BlueMail is given a token that you can control and revoke at any given time.

Sometimes when your provider has made a change to their security policy, they may ask you to reauthorize your account to refresh your OAuth token. BlueMail will prompt you to reauthorize your account when there has been a change to the token by your provider.

For Outlook follow [these steps](/oauth-outlook/).

For Yahoo follow [these steps](/oauth-yahoo/).

For Gmail, follow [these steps](/oauth-gmail/).

You can read about OAuth [here]( http://techcrunch.com/2012/09/17/google-oauth-2-0-for-gmail-and-talk/).