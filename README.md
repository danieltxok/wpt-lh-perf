# WPT & LH Perf Tool Set-up 📱
This is a tool to automate mobile performance testing via <a href="https://www.webpagetest.org/" target="_blank">WebPageTest</a> and <a href="https://developers.google.com/web/tools/lighthouse" target="_blank">Lighthouse</a>.
<br/>
⚠️ If you don't already have a WPT API Key, this won't work for you! ⚠️


## What do you need?
* **WebPagetest API Key**. You need to have one already. WPT does not issue new API Keys.
* **Google account** (e.g. @gmail.com) to fork the Google Sheets tracker and the Data Studio dashboard.


## Do you want to give it a try? 😁

### #1 Set-up the Google Sheets tracker
> Use your Google account to make a copy of <a href="https://docs.google.com/spreadsheets/d/1k8Qr-d2Ze_51975a3t2TcV4jPxrZBWOlCxILBQzNTMw/copy" target="_blank">this template</a> and follow the instructions in the 'How to Use' tab. Remember to keep test settings consistent along time. I would even recommend a single person to be the owner and editor of the file. This file will be the main datasource for the dashboard and it shoud not be modified by others.
<br/><br />
> The video below shows how to set a trigger to automate tests on a daily basis.
<br/><br />
>![How to set a trigger](trigger_demo.gif)
<br/><br />
> Give it a few days and the 'Test' tab wil populate with results for each test.

### #2 Create the dashboard (optional)
> Once the data has populated the 'Tests' tab for a few days, you can make a copy of <a href="https://datastudio.google.com/u/0/reporting/17eCmvvfV62TI9UhM9t-QmX5ASyE2COkm/page/VgD/preview" target="_blank">this Data Studio template</a> and link it to the 'Tests' tab of your tracker by clicking on 'Create a new data source' and linking it to Google Sheets. See the video below.
<br /><br />
>![How to link the tracker](linking_demo.gif)
<br /><br />
> Share the dashboard with the rest of the team!


## Credits 🙏
Thanks **@Antoinebr** for the tracker!
