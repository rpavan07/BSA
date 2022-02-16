## Change in Air Quality due to COVID-19 in parts of India.

After change in Land Cover, wanted to see the how the air quality in India changed due to COVID-19. After reading about the topic, the main data source
I selected was the Copernicus Sentinel 5p dataset. But after much effort, I couldn't get it to work. For some reason, I had trouble installing in some 
of the packages (```matplotlib.basemap```, ```harp```, ```cartopy```). 

I downloaded the images from Copernicus Sentinel 5p using their API in the Level 2 format. Then followed this (https://www.youtube.com/watch?v=CE6BeLPORIE&t=2653s) for
my first attempt. After working on the data, couldn't visualize it because of issues with installing ```cartopy```. Then had issues with installing ```harp```, so couldn't convert 
the L2 images to L3 format.

Same for my second attempt, but couldn't visualize it because of issues with installing ```basemap```.

## References
- RUS Webinar Pollution Monitoring with Sentinel-5p - https://www.youtube.com/watch?v=CE6BeLPORIE&t=2653s
- Data Source - Copernicus 
- https://github.com/derevirn/covid19-pollution
