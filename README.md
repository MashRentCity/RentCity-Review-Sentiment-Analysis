# Tool Functions

## Get Geo Data
get_geo_df()

    return full geo data frame



## Sentiment Scores

### Hu and Lu's 
get_words()

    get positive and negative word sentiments from Hu and Lu's webpage

pos_neg_sentiments(s)

    get positive, negative and different between pos and neg sentiments from Hu and Lu's dictionary of a review

    s: string
        review

### NRC
nrc_emotion_dict()

    get NRC sentiment dictionary

nrc_sentiment(s)

    get NRC sentiments of a review

    s:string 
        reviews


## Text Processing (Used)
get_word_freq_top(s_l, top = 3)

    get top freqent words from a word list

    s_l: list
        word list of reviews
    top: int, option
        number of most freqent words

remove_top_freq(s, freq = 0.05)

    remove top frequent words in a string

    s: string
        reviews
    freq: float, optinal
        frequency boundary
    
get_top_words(s, MAX_count = 5)

    return most frequent words in a string

    s: string
        reviews
    MAX_count: int, optional
        max number of words

get_overlap_words(wc1,wc2)

    return overlapping words in 2 wordclouds

    wc1, wc2: wordcloud
        wordcloud of reviews

removePunc(s)

    remove punctuation in a string

    s: string
        reviews

remove_stop_word(s)

    remove stopping words and words with length smaller than 2 in a string

    s: string
        reviews

emoji_process(s)

    translate emoji to words

    s: string
        reviews

get_noun_adj(s)

    return review with only noun and adj
    
    s: string
        review

## Text Process (Possibly Useful for Future)
remove_at(s)

    remove @ in reviews

    s: string
        reviews

get_hashtag(s)

    get hash tags, counts of hash tags, and string after removing hash tages of reviews

    s: string
        reviews

remove_hyperlink(s)

    remove hyperlink in a string

    s: string
        reviews


## Other Math Calculations

get_arc(a,b)

    return distance between 2 buildings

    a, b : (x,y,z)
        x, y, z coordinates of buildings

norm_eu(x)

    return Euclidean norm of a vector

    x: list
        vector








