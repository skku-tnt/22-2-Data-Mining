# ๐TASK1

### ๐ท์์ธ ํ์ง ๋ถ๋ฅ ์๊ณ ๋ฆฌ์ฆ

- Dataset
    
    [dataset.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aee9482a-1442-4428-9b2f-f5b5ab54b15b/dataset.csv)
    
    [test.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/06e77728-41bb-4c24-be87-2d3acce31a61/test.csv)

- dataset.csv๋ฅผ ์ด์ฉํด์ ์ง๊ธ๊น์ง ๋ฐฐ์ ๋ ๋ด์ฉ์ ๋ฐํ์ผ๋ก ๋ถ์์ ์งํํ์๋ฉด ๋ฉ๋๋ค. ์ ๋ต์ ์์ผ๋ ์์ ๋กญ๊ฒ ์งํํด์ฃผ์ธ์!
    
    ์์ ์์์๋๋ค)
    
    - EDA ( ex) .info(), .head(), .describe() ๋ฑ)
    - ๋ฐ์ดํฐ ์ ์ฒ๋ฆฌ ( ex) object โ numeric, ๊ฒฐ์ธก์น ์ ๊ฑฐ, train_test_split() ๋ฑ)
    - ํ๋ จ
    - ํ๊ฐ ( ex) accuracy, F1 score,  ROC curve ๋ฑ)
    - (์ ํ) test.csv๋ฅผ ํตํ ์๋ก์ด ๋ฐ์ดํฐ์ ๋ํ label๊ฐ ์์ธก
- ์ ๋งํฌ์์์ EDA์ฝ๋์ model ์์ฑ ์ฝ๋๋ฅผ ์ฐธ๊ณ ํ์๋ ์ข์ต๋๋ค!

<์ฃผ์์ฌํญ>

** feature๊ฐ๋ค ์ค โqualityโ๋ฅผ label๋ก ๋๊ณ  ์งํํด์ฃผ์ธ์.

** test.csv ํ์ผ์๋ label๊ฐ์ด ์์ด ์์ธก๊ฐ์ ๋ํ ํ๊ฐ๋ฅผ ์งํํ  ์ ์์ต๋๋ค. dataset.csv ํ์ผ์ ๋ฐ์ดํฐ๋ฅผ ๋ฐํ์ผ๋ก train_test_split()์ ์งํํ์  ํ ์ฌ๊ธฐ์ split๋ test set์ ๋ฐํ์ผ๋ก ์ ๋ต label๊ณผ์ ๋น๊ต๋ฅผ ํตํด ํ๊ฐ๋ฅผ ์งํํด์ฃผ์ธ์.
