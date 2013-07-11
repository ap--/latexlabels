### nice labels for avery 3667 labelpaper ###

I am using onlinetex for this to get the pdf.

Just comment out the **\_numberoflabels** line and add lines like:

    \prettylabel{foo}{bar}{baz}{qux}{qrk}

for each label. Then run and compile with

    python onlinetex/onlinetex prettylabels.tex

done.

(You do need a working internet connection)

