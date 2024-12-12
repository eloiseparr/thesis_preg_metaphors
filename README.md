# thesis_preg_metaphors
Webscraping Online Pregnancy Magazines
Eloise P
23/07/2021
Introduction
Webscraping Mother & Baby articles by week
Week 1
Week 2
Week 3
Week 4
Week 5
Week 6
Week 7
Week 8
Week 9
Week 10
Week 11
Week 12
Week 13
Week 14
Week 15
Week 16
Week 17
Week 18
Week 19
Week 20
Week 21
Week 22
Week 23
Week 24
Week 25
Week 26
Week 27
Week 28
Week 29
Week 30
Week 31
Week 32
Week 33
Week 34
Week 35
Week 36
Week 37
Week 38
Week 39
Week 40
Week 41
Week 42
Webscraping Baby Magazine Articles (https://www.baby-magazine.co.uk/pregnancy/)
Webscraping Absolutely Mama Magazine (https://absolutely-mama.co.uk/?s=pregnan)
Introduction
In this file, we will do the following: 1. scrape the text from online magazines about pregnancy and parenthood 2. save the texts as files

Packages needed:

library(rvest) 
Webscraping Mother & Baby articles by week
Week 1
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/pregnancy-week-by-week/one-week-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page <- html_text(page_html)
write.table(page, file = "one-week-pregnant.txt")
Week 2
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/two-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page2 <- html_text(page_html)
write.table(page2, file = "two-weeks-pregnant.txt")
Week 3
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/pregnancy-symptoms-week-3'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page3 <- html_text(page_html)
write.table(page3, file = "three-weeks-pregnant.txt")
Week 4
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-4-four-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page4 <- html_text(page_html)
write.table(page4, file = "four-weeks-pregnant.txt")
Week 5
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-5-five-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page5 <- html_text(page_html)
write.table(page5, file = "five-weeks-pregnant.txt")
Week 6
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-6-six-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page6 <- html_text(page_html)
write.table(page6, file = "six-weeks-pregnant.txt")
Week 7
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-7-seven-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page7 <- html_text(page_html)
write.table(page7, file = "seven-weeks-pregnant.txt")
Week 8
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-8-eight-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page8 <- html_text(page_html)
write.table(page8, file = "eight-weeks-pregnant.txt")
Week 9
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-9-nine-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page9 <- html_text(page_html)
write.table(page9, file = "nine-weeks-pregnant.txt")
Week 10
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-10-ten-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page10 <- html_text(page_html)
write.table(page10, file = "ten-weeks-pregnant.txt")
Week 11
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-11-eleven-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page11 <- html_text(page_html)
write.table(page11, file = "eleven-weeks-pregnant.txt")
Week 12
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-12-twelve-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page12 <- html_text(page_html)
write.table(page12, file = "twelve-weeks-pregnant.txt")
Week 13
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-13-thirteen-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page13 <- html_text(page_html)
write.table(page13, file = "thirteen-weeks-pregnant.txt")
Week 14
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-14-fourteen-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page14 <- html_text(page_html)
write.table(page14, file = "fourteen-weeks-pregnant.txt")
Week 15
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-15-fifteen-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page15 <- html_text(page_html)
write.table(page15, file = "fifteen-weeks-pregnant.txt")
Week 16
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-16-sixteen-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page16 <- html_text(page_html)
write.table(page16, file = "sixteen-weeks-pregnant.txt")
Week 17
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-17-seventeen-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page17 <- html_text(page_html)
Week 18
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-18-eighteen-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page18 <- html_text(page_html)
write.table(page18, file = "eighteen-weeks-pregnant.txt")
Week 19
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-19-nineteen-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page19 <- html_text(page_html)
write.table(page19, file = "nineteen-weeks-pregnant.txt")
Week 20
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-20-twenty-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page20 <- html_text(page_html)
write.table(page20, file = "twenty-weeks-pregnant.txt")
Week 21
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-21-twenty-one-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page21 <- html_text(page_html)
write.table(page21, file = "twenty-one-weeks-pregnant.txt")
Week 22
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-22-twenty-two-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page22 <- html_text(page_html)
write.table(page22, file = "twenty-two-weeks-pregnant.txt")
Week 23
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-23-twenty-three-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page23 <- html_text(page_html)
write.table(page23, file = "twenty-three-weeks-pregnant.txt")
Week 24
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-24-twenty-four-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page24 <- html_text(page_html)
write.table(page24, file = "twenty-four-weeks-pregnant.txt")
Week 25
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/week-25-twenty-five-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page25 <- html_text(page_html)
write.table(page25, file = "twenty-five-weeks-pregnant.txt")
Week 26
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/26-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page26 <- html_text(page_html)
write.table(page26, file = "twenty-six-weeks-pregnant.txt")
Week 27
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/27-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page27 <- html_text(page_html)
write.table(page27, file = "twenty-seven-weeks-pregnant.txt")
Week 28
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/28-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page28 <- html_text(page_html)
write.table(page28, file = "twenty-eight-weeks-pregnant.txt")
Week 29
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/29-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page29 <- html_text(page_html)
write.table(page29, file = "twenty-nine-weeks-pregnant.txt")
Week 30
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/30-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page30 <- html_text(page_html)
write.table(page30, file = "thirty-weeks-pregnant.txt")
Week 31
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/31-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page31 <- html_text(page_html)
write.table(page31, file = "thirty-one-weeks-pregnant.txt")
Week 32
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/32-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page32 <- html_text(page_html)
write.table(page32, file = "thirty-two-weeks-pregnant.txt")
Week 33
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/33-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page33 <- html_text(page_html)
write.table(page33, file = "thirty-three-weeks-pregnant.txt")
Week 34
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/34-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page34 <- html_text(page_html)
write.table(page34, file = "thirty-four-weeks-pregnant.txt")
Week 35
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/35-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page35 <- html_text(page_html)
write.table(page35, file = "thirty-five-weeks-pregnant.txt")
Week 36
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/36-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page36 <- html_text(page_html)
write.table(page36, file = "thirty-six-weeks-pregnant.txt")
Week 37
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/37-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page37 <- html_text(page_html)
write.table(page37, file = "thirty-seven-weeks-pregnant.txt")
Week 38
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/38-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page38 <- html_text(page_html)
write.table(page38, file = "thirty-eight-weeks-pregnant.txt")
Week 39
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/39-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page39 <- html_text(page_html)
write.table(page39, file = "thirty-nine-weeks-pregnant.txt")
Week 40
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/40-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page40 <- html_text(page_html)
write.table(page40, file = "forty-weeks-pregnant.txt")
Week 41
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/41-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page41 <- html_text(page_html)
write.table(page41, file = "forty-one-weeks-pregnant.txt")
Week 42
url <- 'https://www.motherandbaby.co.uk/pregnancy/week-by-week/42-weeks-pregnant'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.img-responsive+ .padding-bottom-10 , .margin-bottom-25 .margin-bottom-10')
page42 <- html_text(page_html)
write.table(page42, file = "forty-two-weeks-pregnant.txt")
Webscraping Baby Magazine Articles (https://www.baby-magazine.co.uk/pregnancy/)
url <- 'https://www.baby-magazine.co.uk/throwing-a-baby-shower/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "throwing-a-baby-shower.txt")
url <- 'https://www.baby-magazine.co.uk/pregnancy-essentials-trimester-by-trimester/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "pregnancy-essentials-trimester-by-trimester.txt")
url <- 'https://www.baby-magazine.co.uk/pregnancy-safe-beauty-box/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "pregnancy-safe-beauty-box.txt")
url <- 'https://www.baby-magazine.co.uk/a-royal-baby-is-on-the-way-princess-beatrice-is-pregnant-with-her-first-child/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "a-royal-baby-is-on-the-way-princess-beatrice-is-pregnant-with-her-first-child.txt")
url <- 'https://www.baby-magazine.co.uk/hospital-bag-checklist/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "hospital-bag-checklist.txt")
url <- 'https://www.baby-magazine.co.uk/pregnant-covid-19-vaccine-breastfeeding/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "pregnant-covid-19-vaccine-breastfeeding.txt")
url <- 'https://www.baby-magazine.co.uk/charlotte-carroll-film-endometriosis/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "charlotte-carroll-film-endometriosis.txt")
url <- 'https://www.baby-magazine.co.uk/health-teething-problems/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "health-teething-problems.txt")
url <- 'https://www.baby-magazine.co.uk/spring-baby-names/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "spring-baby-names.txt")
url <- 'https://www.baby-magazine.co.uk/maternity-clothes-zara-uk/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "maternity-clothes-zara-uk.txt")
url <- 'https://www.baby-magazine.co.uk/most-popular-royal-baby-names/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "most-popular-royal-baby-names.txt")
url <- 'https://www.baby-magazine.co.uk/give-birth-in-pandemic/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "give-birth-in-pandemic.txt")
url <- 'https://www.baby-magazine.co.uk/best-at-home-workouts/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "best-at-home-workouts.txt")
url <- 'https://www.baby-magazine.co.uk/covid-19-pregnancy-coronavirus-advice-pregnant/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "covid-19-pregnancy-coronavirus-advice-pregnant.txt")
url <- 'https://www.baby-magazine.co.uk/the-ultimate-baby-book/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "the-ultimate-baby-book.txt")
url <- 'https://www.baby-magazine.co.uk/bespoke-postnatal-mot/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "bespoke-postnatal-mot.txt")
url <- 'https://www.baby-magazine.co.uk/postnatal-depression-causes-symptoms-and-treatment/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "postnatal-depression-causes-symptoms-and-treatment.txt")
url <- 'https://www.baby-magazine.co.uk/most-popular-baby-names-for-christmas-revealed/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "most-popular-baby-names-for-christmas-revealed.txt")
url <- 'https://www.baby-magazine.co.uk/my-essentials-jade-holland-cooper/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "my-essentials-jade-holland-cooper.txt")
url <- 'https://www.baby-magazine.co.uk/lucky-baby-names/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "lucky-baby-names.txt")
url <- 'https://www.baby-magazine.co.uk/covid-19-pregnancy-coronavirus-advice-pregnant/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.td-post-content')
page <- html_text(page_html)
write.table(page, file = "covid-19-pregnancy-coronavirus-advice-pregnant.txt")
Webscraping Absolutely Mama Magazine (https://absolutely-mama.co.uk/?s=pregnan)
url <- 'https://absolutely-mama.co.uk/safe-pregnancy-exercises-with-lucy-mills/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "safe-pregnancy-exercises-with-lucy-mills.txt")
url <- 'https://absolutely-mama.co.uk/pregnancy-and-the-pandemic/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "pregnancy-and-the-pandemic.txt")
url <- 'https://absolutely-mama.co.uk/five-pregnancy-safe-exercises-from-hollie-grant/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "five-pregnancy-safe-exercises-from-hollie-grant.txt")
url <- 'https://absolutely-mama.co.uk/best-maternity-brand-or-product-equis-pregnancy-formula/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "best-maternity-brand-or-product-equis-pregnancy-formula.txt")
url <- 'https://absolutely-mama.co.uk/pregnancy-essentials-must-haves-for-mamas-to-be/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "pregnancy-essentials-must-haves-for-mamas-to-be.txt")
url <- 'https://absolutely-mama.co.uk/top-tips-to-help-relieve-stress-when-pregnant/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "top-tips-to-help-relieve-stress-when-pregnant.txt")
url <- 'https://absolutely-mama.co.uk/help-im-pregnant-do-i-need-to-move-house/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "help-im-pregnant-do-i-need-to-move-house.txt")
url <- 'https://absolutely-mama.co.uk/tips-for-better-sleep-during-pregnancy/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "tips-for-better-sleep-during-pregnancy.txt")
url <- 'https://absolutely-mama.co.uk/benefits-pregnancy-massage/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "benefits-pregnancy-massage.txt")
url <- 'https://absolutely-mama.co.uk/going-private-during-pregnancy/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "going-private-during-pregnancy.txt")
url <- 'https://absolutely-mama.co.uk/ask-experts-back-pain/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "ask-experts-back-pain.txt")
url <- 'https://absolutely-mama.co.uk/camilla-lawrence-six-physio/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "camilla-lawrence-six-physio.txt")
url <- 'https://absolutely-mama.co.uk/the-new-pregnancy-beauty-brand-we-love/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "the-new-pregnancy-beauty-brand-we-love.txt")
url <- 'https://absolutely-mama.co.uk/10-ways-keep-cool-youre-pregnant/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "10-ways-keep-cool-youre-pregnant.txt")
url <- 'https://absolutely-mama.co.uk/love-bb-hug-pregnancy-pillow/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "love-bb-hug-pregnancy-pillow.txt")
url <- 'https://absolutely-mama.co.uk/pregnancy-and-post-natal-workouts-to-suit-you/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "pregnancy-and-post-natal-workouts-to-suit-you.txt")
url <- 'https://absolutely-mama.co.uk/the-aesop-facial-for-pregnancy/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "the-aesop-facial-for-pregnancy.txt")
url <- 'https://absolutely-mama.co.uk/opinion-analyse-size/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "opinion-analyse-size.txt")
url <- 'https://absolutely-mama.co.uk/review-weleda-massage-oils-for-pregnancy/'
webpage <- read_html(url)
page_html <- html_nodes(webpage, '.col-sm-8')
page <- html_text(page_html)
write.table(page, file = "review-weleda-massage-oils-for-pregnancy.txt")
