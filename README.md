# DiseaseTrendsGoogle
Disease Trends of anywhere in the World

*Requirements*: `pip install pytrends`

# How to use?
## Location = 'IN-DL'
+ If you want to find trends for any other country or city just change the Location in Main()

## Change AcuteDisease.txt
If you want to find Trends for Different Diseases just change the input in the file.

## To see Trends for Large Population | Keep these lines Uncommented
    print("Relative Score Graph") 
    show_graph_rel(rel_trend_score_sorted, top_n)
    
## To simply find Top 5 trending Disease | Keep these lines Uncommented and comment the above lines
     print("Trends Score Graph")
     show_graph(trend_score_sorted, top_n)
     
#### Hypothesis: A disease is defined here Trending based on it's Search Interest. More search by people for a disease would we done when a large number of people are suffering from a disease.

### Author
Shaurya Uppal [shauryauppal00111@gmail.com]
