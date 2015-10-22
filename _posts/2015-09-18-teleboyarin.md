---
layout: post
title:  "Teleboyarin—Mechanical Tsar for Telegram"
author: "Dmitry Ustalov"
date:   2015-09-18 18:29:53
---

**Teleboyarin** is an open source instant messaging bot designed for crowd annotation via Telegram.

[Telegram](https://telegram.org/) is a cross-platform instant messaging system that provides a convenient [Bot API](https://core.telegram.org/bots/api) for building chatbots, which interact with a user or with a group of users. The API provides additional methods for augmenting communication, e.g. rich text formatting, input completion, command lists, etc.

The three-tier architecture of [Mechanical Tsar](/) requires annotation bot to implement the *application* layer, i.e. it should identify users, provide them with tasks, receive answers from them and deliver the corresponding data from and to the engine over its API. Since all the Telegram users get a unique user identifier (ID) verified by a cell phone number, it is sufficient to represent the users with the above mentioned IDs in order to eliminate the identification problem.

<div class="pure-g">
<div class="pure-u-1-2 pure-u-md-1-4">
<img src="https://media.githubusercontent.com/media/mtsar/mtsar.github.io/master/media/20150918_teleboyarin-1.png" alt="Selecting a process to annotate.">
</div>
<div class="pure-u-1-2 pure-u-md-1-4">
<img src="https://media.githubusercontent.com/media/mtsar/mtsar.github.io/master/media/20150918_teleboyarin-2.png" alt="Choosing an answer for the task.">
</div>
<div class="pure-u-1-2 pure-u-md-1-4">
<img src="https://media.githubusercontent.com/media/mtsar/mtsar.github.io/master/media/20150918_teleboyarin-3.png" alt="Deciding to stop for now.">
</div>
<div class="pure-u-1-2 pure-u-md-1-4">
<img src="https://media.githubusercontent.com/media/mtsar/mtsar.github.io/master/media/20150918_teleboyarin-4.png" alt="Being appreciated.">
</div>
</div>

Source code of Teleboyarin is available on GitHub under the [MIT license](https://opensource.org/licenses/MIT): <https://github.com/mtsar/teleboyarin>. Indeed, similar functionality could be implemented in other messaging systems like Jabber, Slack, WhatsApp, etc.

*Updated: October 13, 2015.* A short paper on Teleboyarin is accepted for publication in proceedings of the [AINL-ISMW FRUCT 2015](https://nlpub.ru/AINL-ISMW_FRUCT) conference.
