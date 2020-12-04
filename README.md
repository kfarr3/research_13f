# research_13f
Research into 13F Holdings

## Files

### 13fs.ipynb

beginning feature engineering, calculates `turn over` based on known data as a proxy for actual fund turn over.  

### 13f_DTW.ipynb

Dynamic Time Warping, attempted temporal clustering of funds with kmeans.  
Results were poor.  Some obvious clustering mostly near zero.

### NEXT

As I've sat on this problem for a bit, while DTW seemed novel, it was much too naive.  The intention again, is to identify similar funds but with slight change in attributes.  For instance, personally, I want funds that respond similar to BRK, long holding periods and high concentration BUT I want them with smaller cap funds than BRK could buy.

I think this is a high-dimension sparse recommendation problem.  Not having experience with that, will spend some time researching the Netflix-Problem and see what SOTA is and how best to attack this.
