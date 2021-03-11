# News sources data for "Split Screen"
The list of news sources we used for [Split Screen](https://themarkup.org/citizen-browser/2021/03/11/split-screen).

You can read our methodology for Split Screen [here](https://themarkup.org/citizen-browser/2021/03/11/how-we-built-a-facebook-feed-viewer). Our methodology for the overall Citizen Browser project is described in "[How We Built a Facebook Inspector](https://themarkup.org/citizen-browser/2021/01/05/how-we-built-a-facebook-inspector)."

For our Citizen Browser project [Split Screen](https://themarkup.org/citizen-browser/2021/03/11/split-screen), we highlighted the news sources that appeared on our panelists’ Facebook feeds. 

To decide what urls should be considered news, we needed a list of news domain names to match against. There isn’t one authoritative source for such a list, and it is constantly changing. Even the definition of “news” is subjective and open to interpretation based on the context in which it is being used. 

## News sources

Our list was compiled from several sources. Facebook’s analytics firm [CrowdTangle](https://www.crowdtangle.com/) curates a wide variety of news source lists, and we used several of these to create a master list including: 

- “All Media”
- “Black Press”
- “Local Media - Broadcast”
- “Local Media - Newspapers & Digital Sites”
- “Local Media (Full List)”
- “US Science & Tech pubs”
- “US Family & Relationship Pubs”
- “US Entertainment Media”
- “US Lifestyle Pubs”
- “US Food Publishers”
- “US Latinx Media”
- “US Music Media”
- “US Sports Media”
- “US Wellness Pubs”
- “US Home & Living Pubs”
- “US Consumer/Shopping Pubs”
- “US Special Interest Pubs”
- “US Style Publications”
- “US Travel & Adventure Pubs”
- “US Beauty Publishers”
- ”US College Newspapers”
- “US General Media”
- “US Top Newspapers”
- “US Political Media”

These source lists were compiled on **Feb. 18, 2021**. 

We then included a large list of sources from “[Local News Dataset 2018](https://github.com/yinleon/LocalNewsDataset)” from The Markup’s Leon Yin.

From this broad list, we sought to filter our list to sharpen the focus on what what we termed “hard news.”

We considered “hard news” to include: 
- National, international and local news
- Breaking news
- Science and technology
- Business
- Politics and political opinion 

We excluded sources we determined to be “soft news”: 
- Entertainment: music, TV, movies
- Celebrity news
- Gossip
- Sports
- Astrology
- Recipes and cooking
- Fashion and style
- Lifestyle
- Religion
- Travel
- Special interests (cars, golf, guns, scuba diving etc)
- Comedy 

We also excluded government entities and specialized trade publications that did not cover general news. 

After filtering out these categories, we ended up with just under 7,000 news sources. 

## Limitations

We made no effort to make any ideological classification for any source. We wanted content that was written and posted by journalists for regular readers all over the world. 

Due to the large dataset, and the turbulent news industry, this should be viewed as a snapshot in time of news sources for March 2021. We made our best attempt to remove broken and incorrect links. 

The process of deciding what is “hard” and “soft” news is subjective, and imprecise. 

We are sharing our final list of filtered “hard news” sources. 

## Data Dictionary

<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: left;">
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>source</strong></td>
      <td>The name of the news source.</td>
    </tr>
    <tr>
      <td><strong>url_domain</strong></td>
      <td>The URL of the news source.</td>
    </tr>
  </tbody>
</table>
 
## Data
**[split_screen_news_sources.csv](https://raw.githubusercontent.com/the-markup/split-screen-news-sources/main/split_screen_news_sources.csv?token=AADIYQZNA4LGC5KBLZY7FOTAKKJJK)**
*228 KB. 6,989 rows. First row is the header.*


## Licensing
Copyright 2021, The Markup News Inc.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.