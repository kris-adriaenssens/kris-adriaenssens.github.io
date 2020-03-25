# TV-kanalen.net
Following test website is created as part of a learning exercise.
The webpage is available at:
1. Production URL [www.TV-kanalen.net](http://www.tv-kanalen.net/)
2. Sandbox URL [kris-adriaenssens.github.io](https://kris-adriaenssens.github.io)

## Platform Selection
1. [Bootstrap4](https://www.w3schools.com/bootstrap4) is used to have a responsive mobile friendly website.
2. An online favicon [Generator](https://favicon.io/favicon-generator/) was used
## Search Engine Optimization (SEO)
1. [Google Trends](https://trends.google.com/trends) is used to find popular search strings. The keywords have been used in the HTML metadata.
2. The website is registered via [Google Search Console](https://www.google.com/webmasters), this makes it possible to analyze search results.
## Website Validation
1. To validate the webpage the [Google Mobile-Friendly](https://search.google.com/test/mobile-friendly?) test is used.
2. To validate the webpage load speed [Google PagesSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) is used.
3. To validate Accessibility and SEO the Audit feature of the chrome Browser is used.

![Google Chrome Audit Feature](/GoogleChromeAudit.png "Google Chrome Audit")
## Website Analytics Collection
Google analitycs is also added to this website for learning.
1. [Google Tag Manager](https://tagmanager.google.com/) is used to add a Tag to the website:
![Google Tag Manager](/GoogleTagManager.png "Google Tag Manager Studio")

2. [Google Analytics](https://analytics.google.com/analytics/web) is used to collect all webpage statistics:
![Google Analytics](/GoogleAnalytics.png "Google Analytics")
3. [Google URL Builder](https://ga-dev-tools.appspot.com/campaign-url-builder/) is used to create campaign specific URL's.

## Website Analytics Reporting
1. [Google DataStudio](https://datastudio.google.com) is used to create HTML reports.
![Google Data Studio](/GoogleDataStudio.png "Google Data Studio")
The report is available at:
[Google Data Studio](https://datastudio.google.com/reporting/e37b9103-072b-4c9e-a2a1-8fb537420142/page/6zXD?s=j6wpkTVsqHo)

2. Google sheets is used to import the data in spreadsheet format and to also publish this data in chart format on the web.
![Google Sheets](/GoogleSheets.png "Google Sheets")
3. Google Sites is used to publish an HTML report with the Google sheet chart statistics on the web.
![Google Sites](/GooglePages.png "Google Pages")
The report is available at:
[Google sites](https://sites.google.com/view/tv-kanalen-net-report/home)

## Website Troubleshooting
[Google Tag assistant](https://get.google.com/tagassistant/) is used to check the tags fired by the webpage.

## Website Deployment
The action workflow deploy.yaml is used to automaticaly deploy the index.html file to the production website after each commit to the master branch. 
