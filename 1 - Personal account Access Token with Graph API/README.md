# Personal account Access Token + Graph API

Use your own Token with **almost full permission** for fetching data. This is the **MOST EFFECTIVE** method.

> Demo: Updating...

## Knowledge

### I. What is Facebook Token?

The Facebook token is a randomly generated code that contains the data associated with the Facebook account. Facebook Token, also known as **Access Token** will contain the permissions to perform an action on the library (API) provided by Facebook. Each Facebook account will have different **Access Tokens**. There may be 1 or more Tokens on the same Facebook account.

There are many ways to reach a destination, but for some reason we will have to choose only one, usually the shortest, fastest path. The **Access Token**is a shortcut to that destination. Understand simply Facebook Token is like that.

### II. What are Facebook tokens used for?

Facebook Token is now quite popular in the field of Facebook Marketing, depending on the limit of the permissions of each token. Some popular applications of Facebook Token:

-   Increase Facebook likes and subs.
-   Automatically post on Facebook.
-   Automatically comment, share articles.
-   Automatically interact in groups, pages.
-   ...

It is used for many different purposes, but the main goal is still to automate all manual operations. With Facebook Token, you can use some features that Facebook has not yet supported or supported in some countries. For example, you won't be able to do the feature of enabling the Facebook Avatar protection shield without using tokens (or Extensions) if in some other countries (India, Germany, ...), then you will find the option to enable shields right on the Facebook account itself.

### III. Facebook Token types

There are 2 types of Facebook Tokens: **Token by App** and **Token by Personal Account**. The Facebook Token by App is the safest one, as it will have a limited lifetime and only has some basic permissions to manipulate on pages and groups. So our main focus will on the Facebook **Token by Personal Account**.

### IV. Facebook Token by Personal Account

This is a **full permissions** token represented by a string of characters starting with `EAA...`, the purpose of this token is to represent your Facebook account to perform actions you can do on Facebook, such as sending messages, like pages, and posts to groups through `API`. Compared to **Token by App**, this token has a longer lifetime and more authority. To make it easier to understand what **Token by App** can do, **Token by Personal Account** can also, but not vice versa.

An example of using this token is that you want to post simultaneously to many groups and many pages; to do this, you cannot log in to each page or group to post because it will be very time-consuming. Just fill in a list of group and page ids, then call an `API` to post them all. Or as you often see on the market, there are tools to increase fake likes, and fake comments are also using this trick.

Note that using Facebook token can save you time, but you should not disclose this token to others because they can abuse it for bad purposes, by:

-   Do not download extensions to get tokens or login your phone number and password to websites that support getting tokens because your information will be exposed.
-   And if you suspect your token has been exposed, immediately change your Facebook password and delete the extensions installed in the browser. Or if you are more careful you can turn on **two-factor authentication** (2FA).

👉 To ensure the safety of using Facebook tokens for personal purposes and save time, as mentioned above, you should use the method of getting tokens directly on Facebook by following the steps below.

## Implement data extraction with Graph API

The source of this method is reused from [FBMediaDownloader](https://github.com/HoangTran0410/FBMediaDownloader) with a few more features added

Updating...