## Done so far
We kept working on the R implementation, as we felt more comfortable after working on it through milestone 3.
The dashboard doesn't look a lot like its sketch, as many elements were added and modified on the way, as we felt it was too simplified.

## To do
### Fixes:
* The cards in the last tab don't update with the filters in the sidebar
* The tooltips in tab 3's plot are broken. They don't show the message they should
* Customized color themes break the dashboard when they are implemented, despite working outside the dashboard

## Limitations
The underlying data is very limited, as it doesn't allow us to view more recent information or sales numbers in currency, only in units sold.
We looked into scraping updated numbers from https://www.vgchartz.com/ but due to the current state of the website (very slow), this does not seem possible.

For example, loading a page on the website takes approximately 15 seconds. With this estimate, it would take approximately 4 days to re-scrape out data. 