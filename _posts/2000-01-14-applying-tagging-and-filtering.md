---
title: Applying Tagging & Filtering
section: Advanced Use
index: 0
---

In WiseCash, you can apply tags to your accounts. Once this is done, you can filter the charts to only take into account the transactions with a given tag. This allows you to achieve **Profit Center Forecasting**.

This is useful to handle the following situations:

* If your business has multiple sub-activities (e.g. consulting + one SaaS product), it is challenging to visualize the upcoming profits or the runway of each of these sub-activities. Tagging allows you to filter the [runway estimation,Balance Forecast & Runway Estimation] and other charts.
* You can tag by people in your team if you want to track a yearly income goal per collaborator, or do an expenses vs. income analysis.
* You can use tags to group similar expenses (e.g. taxes, saas subscriptions) then get a [yearly income forecast,Yearly Income Tracking] and anticipate  difficult months.

Fine! Now, here is how to use tags:

## Enable the tagging add-on

This feature is an add-on, so first make sure to enable it from your settings ({% icon fa-cog %} icon):

{% include screenshot.html file="enabling-tagging-add-on.png" %}

## Tag your accounts

To apply tags, go to the [Account Overview] (icon {% icon fa-search %}) page and click **edit**:

{% include screenshot.html file="edit-account.png" %}

Add your tag or reuse an existing one, then click **Save**:

{% include animation.html file="account-edit-tags.gif" %}

## Review your accounts

It is important to verify that you didn't miss any related transactions while applying your tags.

The best place to do that for now (until a full blown accounts list is made available in WiseCash, which is in the works) is to go the entries listing (icon {% icon fa-list %})

{% include screenshot.html file="reaching-transactions-listing.png" %}

## Visualize your Profit Center Forecast

From there, you can filter all the charts with your new tag to analyze the sub-segment of your business activity. Only the transactions tagged with **at least one tag** will be kept in the calculation:

{% include animation.html file="chart-filtering.gif" %}
