# Popularity of ”NASA” on Twitter after the Artemis programme announcement based on days before and after the Artemis announcement: A Study

## Code used for obtaining results
We made use of a bash script within the twitter corpora from the karora server of the RUG.
We made use of the grep command to match "NASA", -iw made sure uppercase didnt matter and it could match only "NASA". We furtherly used wc -w to count the amount of times nasa was mentioned instead of scrolling through all nasa mentions. The *.out.gz made sure that the code was runnable by day instead of manually filling the hours in.

## Code: 
You could also run the code as zless /net/corpora/twitter2/Tweets/2017/12/201712??\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w
This takes the whole month and counts all mentions in one go, however this took to long and we wanted to have the data per day.
Per day:
(December 1)\
zless /net/corpora/twitter2/Tweets/2017/12/20171201\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 2)\
zless /net/corpora/twitter2/Tweets/2017/12/20171202\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 3)\
zless /net/corpora/twitter2/Tweets/2017/12/20171203\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 4)\
zless /net/corpora/twitter2/Tweets/2017/12/20171204\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 5) \
zless /net/corpora/twitter2/Tweets/2017/12/20171205\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 6) \
zless /net/corpora/twitter2/Tweets/2017/12/20171206\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 7)\
zless /net/corpora/twitter2/Tweets/2017/12/20171207\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 8)\
zless /net/corpora/twitter2/Tweets/2017/12/20171208\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 9)\
zless /net/corpora/twitter2/Tweets/2017/12/20171209\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 10)\
zless /net/corpora/twitter2/Tweets/2017/12/20171210\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 11)\
zless /net/corpora/twitter2/Tweets/2017/12/20171211\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 12)\
zless /net/corpora/twitter2/Tweets/2017/12/20171212\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 13)\
zless /net/corpora/twitter2/Tweets/2017/12/20171213\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 14)\
zless /net/corpora/twitter2/Tweets/2017/12/20171214\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 15)\
zless /net/corpora/twitter2/Tweets/2017/12/20171215\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 16)\
zless /net/corpora/twitter2/Tweets/2017/12/20171216\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 17)\
zless /net/corpora/twitter2/Tweets/2017/12/20171217\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 18)\
zless /net/corpora/twitter2/Tweets/2017/12/20171218\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 19)\
zless /net/corpora/twitter2/Tweets/2017/12/20171219\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 20)\
zless /net/corpora/twitter2/Tweets/2017/12/20171220\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 21)\
zless /net/corpora/twitter2/Tweets/2017/12/20171221\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 22)\
zless /net/corpora/twitter2/Tweets/2017/12/20171222\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 23)\
zless /net/corpora/twitter2/Tweets/2017/12/20171223\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 24)\
zless /net/corpora/twitter2/Tweets/2017/12/20171224\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 25)\
zless /net/corpora/twitter2/Tweets/2017/12/20171225\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 26)\
zless /net/corpora/twitter2/Tweets/2017/12/20171226\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 27)\
zless /net/corpora/twitter2/Tweets/2017/12/20171227\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 28)\
zless /net/corpora/twitter2/Tweets/2017/12/20171228\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 29)\
zless /net/corpora/twitter2/Tweets/2017/12/20171229\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 30)\
zless /net/corpora/twitter2/Tweets/2017/12/20171230\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w \
(December 31)\
zless /net/corpora/twitter2/Tweets/2017/12/20171231\:*.out.gz  | /net/corpora/twitter2/tools/tweet2tab -i text | grep -iw "nasa" | wc -w 

