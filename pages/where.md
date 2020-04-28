![](where_files/figure-markdown_strict/unnamed-chunk-1-1.png)![](where_files/figure-markdown_strict/unnamed-chunk-1-2.png)![](where_files/figure-markdown_strict/unnamed-chunk-1-3.png)

### What's the temperature where we are? Using Google's BigQuery API

In one homework assignment, students connected to [Google's BigQuery
API](https://cloud.google.com/bigquery/public-data "BigQuery Public Data")
to access a public dataset containing weather information collected by
NOAA. They identified a weather station in the state or country in which
they were currently residing, and plotted the average temperature by
month in their location.

    ## trying token_fetch()
    ## trying credentials_service_account()
    ## Error: lexical error: invalid char in json text.
    ##                                        Stat231-Lab9b-Test-0d94d10c3b24
    ##                      (right here) ------^
    ## 
    ## trying credentials_app_default()
    ## trying credentials_gce()
    ## trying credentials_byo_oauth()
    ## Error: inherits(token, "Token2.0") is not TRUE
    ## trying credentials_user_oauth2()
    ## Gargle2.0 initialize
    ## attempt from: bigrquery
    ## adding 'userinfo.email' scope
    ## loading token from the cache
    ## Using an auto-discovered, cached token.
    ## To suppress this message, modify your code or options to clearly consent to the use of a cached token.
    ## See gargle's "Non-interactive auth" vignette for more details:
    ## https://gargle.r-lib.org/articles/non-interactive-auth.html
    ## The bigrquery package is using a cached token for kcorreia@amherst.edu.
    ## matching token found in the cache

![](where_files/figure-markdown_strict/unnamed-chunk-2-1.png)

Dear March - Come in Emily Dickinson

Dear March - Come in - How glad I am - I hoped for you before -  
Put down your Hat -  
You must have walked -  
How out of Breath you are - Dear March, how are you, and the Rest - Did
you leave Nature well - Oh March, Come right upstairs with me - I have
so much to tell -

I got your Letter, and the Birds - The Maples never knew that you were
coming - I declare - how Red their Faces grew - But March, forgive me -
And all those Hills you left for me to Hue - There was no Purple
suitable - You took it all with you -

Who knocks? That April - Lock the Door - I will not be pursued - He
stayed away a Year to call When I am occupied - But trifles look so
trivial As soon as you have come

That blame is just as dear as Praise And Praise as mere as Blame -
