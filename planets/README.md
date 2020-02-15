# www.howmanyplanetsarethere.com

[howmanyplanetsite - github](https://github.com/dylanharper/howmanyplanetssite)

A static site hosted on Google Storage.

Data is collected by [vaqmr](https://github.com/dylanharper/vaqmr) (web_scrape) and processed by [husker](https://github.com/dylanharper/husker) before being sent to redis, where the new data will get picked up by a regularly scheduled google function called [update_planets_site](https://github.com/dylanharper/howmanyplanetssite/blob/1a570d1bfa344e9b659dd849191ea08b6be79b17/main.py#L46)
