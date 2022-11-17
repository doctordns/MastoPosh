# MastoPosh - PowerShell Folks on Mastodon

## Introduction

Mastodon is a federated social media platform with server instances world wide.
With the shenanigans over at the Bird Place, Mastodon is seeing a huge grown in users, including PowerShell users.
One can just follow the #PowerSHell hash tag to get a lot of great content - and follow the posters of more interesting content.
For folks that are new to #Mastodon, the list here is a start6ing point.

Automation of Mastodon setup is another longer term goal.
I'd like to be able to offer some scripts that enable you to follow the folks on the list.

## This repository

This repo contains a file ``mastoposh.csv`` which is a comma separated value file of PowerShell users on Mastodon.

## Contents of mastoposh.csv

This file contains a list of #PowerShell folks on Mastodon and their co-ordinates.
The file is in CSV format and I maintain it using Excel

The CSV 5 fields (currently):
* `Name` - your name
* `MastonAddress` - your mastodon address, sans the initial "@". Excel complains about it and I've not found a work around - yet.
* `ShowBoosts` - Whether you want to have boosts shown (4.0 and later) - Y or N
* `NotifyNewPost` - Whether you want to see new posts (4.0 and later) -  Y or N
* `Language` - what languages are you happy with - a comma separated list of language names (eg EN, EN-GB, etc;)

If you see errors in this list, please raise a GitHub issue (or issue a PR).

> ** _NOTE:_ ** The field names in this CSV _*may*_ change. 
> If the automation requires different field names, the heading names here may change so as t6o simplify using this file gooiung forward.



## In Closing

If you are NOT on this list, but want to, issue a PR with your details and I'll action it as quickly as possible. 
Be careful with PRs as two folks might want to chance the CSV and issue 'competing' PRs.
I will of course hand correct the later PR so the update will not get lost.

My email is DoctorDNS@Gmail.Com


And please - sending me Toots about this list may work but I may miss them too!
Consider using Github and raising a PR?
