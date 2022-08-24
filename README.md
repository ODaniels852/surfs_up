# An Analysis of Climate Data

## Project Overview
In an attempt to make a longterm move to Hawaii I have decided to invest in a business in Hawaii, specifically a surf and ice cream shop business. After putting together a strong business plan I've reached out an an investor, W. Avy, who has agreed to invest but has shared concerns about the weather. He has asked that I run analytics on a weather dataset he has from Oahu, the island where I'd like to open my  business. W. Avy liked my intital analysis, but wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.   

### Results
<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/surfs_up/raw/main/analysis/june_temps_df.png">
<img alt=" Shows June temperature results."/>

</picture>

<picture>
 <source media="(prefers-color-scheme: light)" srcset="https://github.com/ODaniels852/surfs_up/raw/main/analysis/dec_temps_df.png">
<img alt=" Shows December temperature results."/>

</picture>


- Average temperatures in June are around 75 degrees, while average temperatures in December are around 71 degrees
- In June temperatures can get as low as about 64 degrees, while in December temperatures can get as low as about 56 degrees
- In June temperatures can get as high as about 85 degrees, while in December temperatures can get as high as about 83 degrees

Based on analysis results this apepars to be a great investment, and hopefully one that  W. Avy ultimately agrees to. While temperatures do drop a bit in December, it still gets warm enough to warrant ice cream purchases indicating year-round sustainability for th business. For additional review, a query can be run to determine the count of days within November and Decmber during which temperatures are below 60 degrees which would indicate potention lower sales for those days. Similarly, a query can be run to determine the count of days within November and Decmber during which temperatures are above 75 degrees which would indicate potention higher sales for those days. 