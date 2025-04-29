# asgmt-02-python-for-non-stem
Assignment 02: Python for Non-STEM.

## 練習題指引

- 將練習題的 GitHub Repository 下載到自己的電腦，解壓縮後以 VS Code 開啟專案資料夾。
- 先閱讀 `README.md`，再將答案寫在 `answers.py`
- 練習題共分為三種：
  - 是非題：預設答案 `answer_01 = None`，請以布林型別宣告答案，若覺得是非題的敘述**不正確**，就宣告 `answer_01 = False`，若覺得是非題的敘述**正確**則宣告 `answer_01 = True`
  - 單選題：預設答案 `answer_02 = None`，請以整數型別宣告答案，若覺得單選題的第一個選項**正確**宣告為 `answer_02 = 1`，若覺得單選題的第二個選項**正確**則宣告 `answer_02 = 2`，若覺得單選題的第三個選項**正確**則宣告 `answer_02 = 3`，若覺得單選題的第四個選項**正確**則宣告 `answer_02 = 4`
  - 程式題：以函數/類別宣告答案，函數/類別名稱下的長字串（docstring）會描述測試資料與預期輸出，能夠讓我們充分暸解預期輸入以及預期輸出之間的對應關係，寫作完畢後要記得輸出答案的變數 `return your_answer_variable`
- 如果練習題需要載入檔案，檔案會與練習題存放在同個資料夾中，這時可以運用工作目錄的相對路徑直接指定檔案名稱載入。
- 寫作完成後將 `answers.py` 存檔，再執行專案資料夾中的 `test_runner.py` 進行測試，再依照測試結果修正答案或截圖測試結果繳交作業。

## 01.（是非題）在函數的組成要件中，輸入與參數在定義上是完全相同、沒有差別的。

```python
answer_01 = None
```

## 02.（單選題）下列哪一個物件的命名是有效的？

1. `def = "define"`
2. `is_python_great = True`
3. `5566_is_my_favorite_group = True`
4. `247StandsFor = "24 hours a day, 7 days a week."`

```python
answer_02 = None
```

## 03.（單選題）下列何者是 Python 的內建（標準）函數？

1. `mean()`
2. `median()`
3. `sum()`
4. `average()`

```python
answer_03 = None
```

## 04.（程式題）使用內建函數 `abs()` 計算輸入整數的絕對值。

Reference: <https://docs.python.org/3/library/functions.html>

```python
def answer_04(x) -> float:
    """
    >>> answer_04(-3)
    3
    >>> answer_04(4)
    4
    >>> answer_04(-5)
    5
    """
```

## 05.（程式題）使用內建函數 `pow()` 為輸入整數開平方根並回傳正的運算結果。

Reference: <https://docs.python.org/3/library/functions.html>

```python
def answer_05(x) -> float:
    """
    >>> answer_05(9)
    3.0
    >>> answer_05(16)
    4.0
    >>> answer_05(25)
    5.0
    """
```