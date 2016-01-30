Title: Citation Searching on CourtListener
Summary: Our new citation searching feature allows you to slice and dice the citations to any opinion.
Author: mlissner
Date: 2016-01-30 18:00:00
Tags: announcements, citations, courtlistener
Status: Draft


One of the great new features that [the new version of CourtListener][1] provides is what we're calling Citation Searching. Citation Searching lets you look at all the opinions that cite an opinion you're interested in and then slice and dice them so that you only see the ones that are important to you.

For example, say you're looking at [Roe v. Wade][roe] and you want to analyze the cases that have cited it. In the sidebar on the left, there's a list of the opinions citing the one you're looking at, in the section called "Cited By". At the bottom of that section, there's a link that says, "Full List of Cited Opinions".

![Sidebar]()

If you click that link, you'll be taken back to the search results page, and you'll see that your query is for `cites:(108713)`. The XXXCOUNTXXX results that are shown can now be filtered however you like.

Let's assume that you want to look for cases citing Roe v. Wade that have the phrase "Planned Parenthood". To do that, we'll change the query to `cites:(108713) "planned parenthood"`.

![PP Query]()

That brings the number of cases that cite Roe v. Wade to only XXXX cases, but that's still a lot to review. Perhaps you can filter down to only federal cases using [the Jurisdiction Picker][picker]. If you do that, you will have XXX opinions remaining, and you can sort them by relevancy to see which ones to review.


## Citation Alerts

Another fascinating use of this new tool is to tie it in with our alert system. If you're logged into CourtListener, and you're looking at search results, you'll always see a sidebar that allows you to create an alert.

![Alert Sidebar]()

Now that you have a query that you like (all cases citing Roe v. Wade in federal jurisdictions containing the phrase "Planned Parenthood"), you can create an alert so that whenever a new case fits these criteria you get an email sent to you at the end of the day, week, or in [real time][rt], if you're a Free Law Project supporter.

As always, you can also set up an RSS feed for any query, if you're familiar with that technology.

Citation searching is a feature that we've wanted to deploy for a long time, ever since we realized it was possible. We're sure it's going to become a valuable part of your research process, and we hope if you have any ideas for making it better that you'll let us know!


[1]: {filname}/brand-new-courtlistener-a-year-in-the-works.md
[roe]: https://www.courtlistener.com/opinion/108713/roe-v-wade/
[picker]: {filename}/our-new-jurisdiction-picker.md
[rt]: {filename}/courtlistener-will-now-send-alerts-in-real-time.md