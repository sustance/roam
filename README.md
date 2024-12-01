# Roam

#______TRAVEL Next Trips Book_____

1.  All pdfs for a single name prefix (trip) for the first day af travel on that trip

2.  Get PDFs of all ticket and in target folder with names YYYMMDDi-* where "i" sets sequence within date.

3.  run: incpdfTravel.lua 20241210 YYMMDD <-- for trips to include in this book

- Script 1-*.sh

4.  Cut and paste that output to NextTickets.tex 
    NOTE This can be automated but this should enable the book to be recreated without keeping a cpy)

5.  Compile NextTickets.tex with LuaTeX
    NOTE this will give a random number of pages and must be still be adjusted to fit 8 page signatures

-  Script 2-*.sh

6.  Compile signaturesX8.tex

- Script 3-*.sh
