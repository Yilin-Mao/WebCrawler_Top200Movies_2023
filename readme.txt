This is the package for assignment_1.pdf aiming to get information of top 200 movies in 2023 mainly from www.boxofficemojo.com.

The codes are all included in code.ipynb and are seperated by markdown block.

For 1.1, the code first gets the text from the website using requests and BeautifulSoup, then most information of top 200 movies like rank and worldwide box could be found. The movie id is a little hard which needs the link url of each movie and can be done by link.get('herf').

Knowing the movie id, we get replace the link and open each movie's website then get introduction using soup.find('p', class='...'). That's 1.2.

1.3 is similar, the only thing to change is soup (soup..certain class...find_all(img))

2.4 uses tutorial. Installing nltk is a little tricky in win10 and text process is a little troublesome (coping with list, str, split is drama)

2.5 and 3.6 are easy which only need example code. However, text process is always a bit troublesome.