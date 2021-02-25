# rstudio

> nummy <- c(2,3,4)
> nummy_int <- c(1L,2L,3L)
> typeof(nummy)
[1] "double"
> typeof(nummy_int)
[1] "integer"
> is.numeric(nummy)
[1] TRUE
> is.numeric(nummy_int)
[1] TRUE
> is.atomic(nummy)
[1] TRUE
> nummy
[1] 2 3 4
> is.double(nnummy_int)
Error: object 'nnummy_int' not found
> is.double(nummy_int
+ )
[1] FALSE
> is.character(nummy)
[1] FALSE
> is.character(nummy_int)
[1] FALSE
> logicals
Error: object 'logicals' not found
> logicals <- c(TRUE,F,TRUE,T, FALSE)
> logicals
[1]  TRUE FALSE  TRUE  TRUE FALSE
> types <- c("int","double","character")
> types
[1] "int"       "double"    "character"
> money_in_chars <- c("20","35","33")
> typeof(money_in_chars)
[1] "character"
> money_money <- as.logical(money_in_chars)
> money_money
[1] NA NA NA
> money_money <- as.numeric(money_in_chars)
> money_money
[1] 20 35 33
> money_logical <- as.logical(money_money)
> money_logical
[1] TRUE TRUE TRUE
> as.logical(c(20, 35, 0))
[1]  TRUE  TRUE FALSE
> as.logical(c(1,1,1))
[1] TRUE TRUE TRUE
> money_money <- as.numeric(money_in_chars)
> money_money
[1] 20 35 33
> typeof(money_money)
[1] "double"
> new_money <- c(money_money,"33","50")
> new_money
[1] "20" "35" "33" "33" "50"
> typeof(new_money)
[1] "character"
> months(x)
Error in months(x) : object 'x' not found
> months.Date()
Error in format(x, ifelse(abbreviate, "%b", "%B")) : 
  argument "x" is missing, with no default
> month
Error: object 'month' not found
> month.name
 [1] "January"   "February"  "March"     "April"     "May"       "June"      "July"      "August"   
 [9] "September" "October"   "November"  "December" 
> month.abb
 [1] "Jan" "Feb" "Mar" "Apr" "May" "Jun" "Jul" "Aug" "Sep" "Oct" "Nov" "Dec"
> month.name[1:3]
[1] "January"  "February" "March"   
> month.name(c(1,2,3))
Error in month.name(c(1, 2, 3)) : could not find function "month.name"
> month.name[c(1,2,3)]
[1] "January"  "February" "March"   
> month.name[c(6,7,12)]
[1] "June"     "July"     "December"
> month.name[c(7,8,12)]
[1] "July"     "August"   "December"
> month.name[7:8],month.name[12]
Error: unexpected ',' in "month.name[7:8],"
> month.name[7:8]
[1] "July"   "August"
> month.name[7:8, 12]
Error in month.name[7:8, 12] : incorrect number of dimensions
> days.abb
Error: object 'days.abb' not found
> date()
[1] "Thu Feb 25 14:28:09 2021"
> days <- c("Mon","Tue","Wed")
> days
[1] "Mon" "Tue" "Wed"
> week_end <- c("Sat","Sun")
> more_days <- c(days,"Thu","Fri",week_end)
> more_days
[1] "Mon" "Tue" "Wed" "Thu" "Fri" "Sat" "Sun"
> days, week_end
Error: unexpected ',' in "days,"
> days
[1] "Mon" "Tue" "Wed"
> new <- c(days, week_end)
> new
[1] "Mon" "Tue" "Wed" "Sat" "Sun"
> objects <- c("Pen","Paper","Book")
> objects
[1] "Pen"   "Paper" "Book" 
> new1 <- c(objects, pencil)
Error: object 'pencil' not found
> new1 <- c(objects, "pencil")
> new1
[1] "Pen"    "Paper"  "Book"   "pencil"
