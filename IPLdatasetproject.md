```python
import pandas as pd
df = pd.read_csv("C:\\Users\\my device\\Downloads\\archive.zip")
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Year</th>
      <th>Player_Name</th>
      <th>Matches_Batted</th>
      <th>Not_Outs</th>
      <th>Runs_Scored</th>
      <th>Highest_Score</th>
      <th>Batting_Average</th>
      <th>Balls_Faced</th>
      <th>Batting_Strike_Rate</th>
      <th>Centuries</th>
      <th>...</th>
      <th>Matches_Bowled</th>
      <th>Balls_Bowled</th>
      <th>Runs_Conceded</th>
      <th>Wickets_Taken</th>
      <th>Best_Bowling_Match</th>
      <th>Bowling_Average</th>
      <th>Economy_Rate</th>
      <th>Bowling_Strike_Rate</th>
      <th>Four_Wicket_Hauls</th>
      <th>Five_Wicket_Hauls</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2024</td>
      <td>Ruturaj Gaikwad</td>
      <td>2</td>
      <td>0</td>
      <td>61</td>
      <td>46</td>
      <td>30.5</td>
      <td>51</td>
      <td>119.61</td>
      <td>0</td>
      <td>...</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2023</td>
      <td>Ruturaj Gaikwad</td>
      <td>16</td>
      <td>1</td>
      <td>590</td>
      <td>92</td>
      <td>42.14</td>
      <td>400</td>
      <td>147.5</td>
      <td>0</td>
      <td>...</td>
      <td>16</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2022</td>
      <td>Ruturaj Gaikwad</td>
      <td>14</td>
      <td>0</td>
      <td>368</td>
      <td>99</td>
      <td>26.29</td>
      <td>291</td>
      <td>126.46</td>
      <td>0</td>
      <td>...</td>
      <td>14</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2021</td>
      <td>Ruturaj Gaikwad</td>
      <td>16</td>
      <td>2</td>
      <td>635</td>
      <td>101*</td>
      <td>45.35</td>
      <td>466</td>
      <td>136.26</td>
      <td>1</td>
      <td>...</td>
      <td>16</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2020</td>
      <td>Ruturaj Gaikwad</td>
      <td>6</td>
      <td>2</td>
      <td>204</td>
      <td>72</td>
      <td>51</td>
      <td>169</td>
      <td>120.71</td>
      <td>0</td>
      <td>...</td>
      <td>6</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>1167</th>
      <td>2022</td>
      <td>Mayank Markande</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>2</td>
      <td>42</td>
      <td>57</td>
      <td>1</td>
      <td>1/26</td>
      <td>57.00</td>
      <td>8.14</td>
      <td>42.00</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1168</th>
      <td>2021</td>
      <td>Mayank Markande</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.00</td>
      <td>0</td>
      <td>0.00</td>
      <td>0</td>
      <td>...</td>
      <td>1</td>
      <td>18</td>
      <td>26</td>
      <td>0</td>
      <td>0/26</td>
      <td>0</td>
      <td>8.66</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1169</th>
      <td>2019</td>
      <td>Mayank Markande</td>
      <td>3</td>
      <td>1</td>
      <td>6</td>
      <td>6</td>
      <td>6.00</td>
      <td>5</td>
      <td>120.00</td>
      <td>0</td>
      <td>...</td>
      <td>3</td>
      <td>36</td>
      <td>59</td>
      <td>1</td>
      <td>1/23</td>
      <td>59.00</td>
      <td>9.83</td>
      <td>36.00</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1170</th>
      <td>2018</td>
      <td>Mayank Markande</td>
      <td>14</td>
      <td>4</td>
      <td>21</td>
      <td>7*</td>
      <td>10.50</td>
      <td>24</td>
      <td>87.50</td>
      <td>0</td>
      <td>...</td>
      <td>14</td>
      <td>264</td>
      <td>368</td>
      <td>15</td>
      <td>4/23</td>
      <td>24.53</td>
      <td>8.36</td>
      <td>17.60</td>
      <td>1</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1171</th>
      <td>No stats</td>
      <td>Jhathavedh Subramanyan</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>...</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
      <td>No stats</td>
    </tr>
  </tbody>
</table>
<p>1172 rows × 25 columns</p>
</div>




```python
df['Player_Name'].nunique()
```




    247




```python
count=0
l=[]
for i in df['Year']:
    count+=1
    if i == 'No stats':
        l.append(count-1)

```


```python
df = df.drop(l)
```


```python
df.shape
```




    (1130, 25)




```python
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Year</th>
      <th>Player_Name</th>
      <th>Matches_Batted</th>
      <th>Not_Outs</th>
      <th>Runs_Scored</th>
      <th>Highest_Score</th>
      <th>Batting_Average</th>
      <th>Balls_Faced</th>
      <th>Batting_Strike_Rate</th>
      <th>Centuries</th>
      <th>...</th>
      <th>Matches_Bowled</th>
      <th>Balls_Bowled</th>
      <th>Runs_Conceded</th>
      <th>Wickets_Taken</th>
      <th>Best_Bowling_Match</th>
      <th>Bowling_Average</th>
      <th>Economy_Rate</th>
      <th>Bowling_Strike_Rate</th>
      <th>Four_Wicket_Hauls</th>
      <th>Five_Wicket_Hauls</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2024</td>
      <td>Ruturaj Gaikwad</td>
      <td>2</td>
      <td>0</td>
      <td>61</td>
      <td>46</td>
      <td>30.5</td>
      <td>51</td>
      <td>119.61</td>
      <td>0</td>
      <td>...</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2023</td>
      <td>Ruturaj Gaikwad</td>
      <td>16</td>
      <td>1</td>
      <td>590</td>
      <td>92</td>
      <td>42.14</td>
      <td>400</td>
      <td>147.5</td>
      <td>0</td>
      <td>...</td>
      <td>16</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2022</td>
      <td>Ruturaj Gaikwad</td>
      <td>14</td>
      <td>0</td>
      <td>368</td>
      <td>99</td>
      <td>26.29</td>
      <td>291</td>
      <td>126.46</td>
      <td>0</td>
      <td>...</td>
      <td>14</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2021</td>
      <td>Ruturaj Gaikwad</td>
      <td>16</td>
      <td>2</td>
      <td>635</td>
      <td>101*</td>
      <td>45.35</td>
      <td>466</td>
      <td>136.26</td>
      <td>1</td>
      <td>...</td>
      <td>16</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2020</td>
      <td>Ruturaj Gaikwad</td>
      <td>6</td>
      <td>2</td>
      <td>204</td>
      <td>72</td>
      <td>51</td>
      <td>169</td>
      <td>120.71</td>
      <td>0</td>
      <td>...</td>
      <td>6</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>1166</th>
      <td>2023</td>
      <td>Mayank Markande</td>
      <td>10</td>
      <td>3</td>
      <td>21</td>
      <td>18*</td>
      <td>0</td>
      <td>13</td>
      <td>161.54</td>
      <td>0</td>
      <td>...</td>
      <td>10</td>
      <td>228</td>
      <td>300</td>
      <td>12</td>
      <td>4/15</td>
      <td>25.00</td>
      <td>7.89</td>
      <td>19.00</td>
      <td>1</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1167</th>
      <td>2022</td>
      <td>Mayank Markande</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>2</td>
      <td>42</td>
      <td>57</td>
      <td>1</td>
      <td>1/26</td>
      <td>57.00</td>
      <td>8.14</td>
      <td>42.00</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1168</th>
      <td>2021</td>
      <td>Mayank Markande</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.00</td>
      <td>0</td>
      <td>0.00</td>
      <td>0</td>
      <td>...</td>
      <td>1</td>
      <td>18</td>
      <td>26</td>
      <td>0</td>
      <td>0/26</td>
      <td>0</td>
      <td>8.66</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1169</th>
      <td>2019</td>
      <td>Mayank Markande</td>
      <td>3</td>
      <td>1</td>
      <td>6</td>
      <td>6</td>
      <td>6.00</td>
      <td>5</td>
      <td>120.00</td>
      <td>0</td>
      <td>...</td>
      <td>3</td>
      <td>36</td>
      <td>59</td>
      <td>1</td>
      <td>1/23</td>
      <td>59.00</td>
      <td>9.83</td>
      <td>36.00</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1170</th>
      <td>2018</td>
      <td>Mayank Markande</td>
      <td>14</td>
      <td>4</td>
      <td>21</td>
      <td>7*</td>
      <td>10.50</td>
      <td>24</td>
      <td>87.50</td>
      <td>0</td>
      <td>...</td>
      <td>14</td>
      <td>264</td>
      <td>368</td>
      <td>15</td>
      <td>4/23</td>
      <td>24.53</td>
      <td>8.36</td>
      <td>17.60</td>
      <td>1</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>1130 rows × 25 columns</p>
</div>




```python
df.dtypes
```




    Year                   object
    Player_Name            object
    Matches_Batted         object
    Not_Outs               object
    Runs_Scored            object
    Highest_Score          object
    Batting_Average        object
    Balls_Faced            object
    Batting_Strike_Rate    object
    Centuries              object
    Half_Centuries         object
    Fours                  object
    Sixes                  object
    Catches_Taken          object
    Stumpings              object
    Matches_Bowled         object
    Balls_Bowled           object
    Runs_Conceded          object
    Wickets_Taken          object
    Best_Bowling_Match     object
    Bowling_Average        object
    Economy_Rate           object
    Bowling_Strike_Rate    object
    Four_Wicket_Hauls      object
    Five_Wicket_Hauls      object
    dtype: object




```python
df['Year'] = pd.to_datetime(df['Year'],format='%Y')
df.info()
```

    <class 'pandas.core.frame.DataFrame'>
    Int64Index: 1130 entries, 0 to 1170
    Data columns (total 25 columns):
     #   Column               Non-Null Count  Dtype         
    ---  ------               --------------  -----         
     0   Year                 1130 non-null   datetime64[ns]
     1   Player_Name          1130 non-null   object        
     2   Matches_Batted       1130 non-null   object        
     3   Not_Outs             1130 non-null   object        
     4   Runs_Scored          1130 non-null   object        
     5   Highest_Score        1130 non-null   object        
     6   Batting_Average      1130 non-null   object        
     7   Balls_Faced          1130 non-null   object        
     8   Batting_Strike_Rate  1130 non-null   object        
     9   Centuries            1130 non-null   object        
     10  Half_Centuries       1130 non-null   object        
     11  Fours                1130 non-null   object        
     12  Sixes                1130 non-null   object        
     13  Catches_Taken        1130 non-null   object        
     14  Stumpings            1130 non-null   object        
     15  Matches_Bowled       1130 non-null   object        
     16  Balls_Bowled         1130 non-null   object        
     17  Runs_Conceded        1130 non-null   object        
     18  Wickets_Taken        1130 non-null   object        
     19  Best_Bowling_Match   1130 non-null   object        
     20  Bowling_Average      1130 non-null   object        
     21  Economy_Rate         1130 non-null   object        
     22  Bowling_Strike_Rate  1130 non-null   object        
     23  Four_Wicket_Hauls    1130 non-null   object        
     24  Five_Wicket_Hauls    1130 non-null   object        
    dtypes: datetime64[ns](1), object(24)
    memory usage: 229.5+ KB
    


```python
df.columns
```




    Index(['Year', 'Player_Name', 'Matches_Batted', 'Not_Outs', 'Runs_Scored',
           'Highest_Score', 'Batting_Average', 'Balls_Faced',
           'Batting_Strike_Rate', 'Centuries', 'Half_Centuries', 'Fours', 'Sixes',
           'Catches_Taken', 'Stumpings', 'Matches_Bowled', 'Balls_Bowled',
           'Runs_Conceded', 'Wickets_Taken', 'Best_Bowling_Match',
           'Bowling_Average', 'Economy_Rate', 'Bowling_Strike_Rate',
           'Four_Wicket_Hauls', 'Five_Wicket_Hauls'],
          dtype='object')




```python
#df.drop(['Balls_Faced', 'Balls_Bowled', 'Stumpings', 'Best_Bowling_Match'], axis=1, inplace=True)
```


```python
df.drop([Stumpings', 'Best_Bowling_Match'], axis=1, inplace=True)
```


      Cell In[76], line 1
        df.drop([Stumpings', 'Best_Bowling_Match'], axis=1, inplace=True)
                                                ^
    SyntaxError: unterminated string literal (detected at line 1)
    



```python
df.info()
```

    <class 'pandas.core.frame.DataFrame'>
    Int64Index: 1130 entries, 0 to 1170
    Data columns (total 25 columns):
     #   Column               Non-Null Count  Dtype         
    ---  ------               --------------  -----         
     0   Year                 1130 non-null   datetime64[ns]
     1   Player_Name          1130 non-null   object        
     2   Matches_Batted       1130 non-null   object        
     3   Not_Outs             1130 non-null   object        
     4   Runs_Scored          1130 non-null   object        
     5   Highest_Score        1130 non-null   object        
     6   Batting_Average      1130 non-null   object        
     7   Balls_Faced          1130 non-null   object        
     8   Batting_Strike_Rate  1130 non-null   object        
     9   Centuries            1130 non-null   object        
     10  Half_Centuries       1130 non-null   object        
     11  Fours                1130 non-null   object        
     12  Sixes                1130 non-null   object        
     13  Catches_Taken        1130 non-null   object        
     14  Stumpings            1130 non-null   object        
     15  Matches_Bowled       1130 non-null   object        
     16  Balls_Bowled         1130 non-null   object        
     17  Runs_Conceded        1130 non-null   object        
     18  Wickets_Taken        1130 non-null   object        
     19  Best_Bowling_Match   1130 non-null   object        
     20  Bowling_Average      1130 non-null   object        
     21  Economy_Rate         1130 non-null   object        
     22  Bowling_Strike_Rate  1130 non-null   object        
     23  Four_Wicket_Hauls    1130 non-null   object        
     24  Five_Wicket_Hauls    1130 non-null   object        
    dtypes: datetime64[ns](1), object(24)
    memory usage: 229.5+ KB
    


```python
df['Highest_Score'] = df['Highest_Score'].str.replace(r'\*', '', regex=True)
df

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Year</th>
      <th>Player_Name</th>
      <th>Matches_Batted</th>
      <th>Not_Outs</th>
      <th>Runs_Scored</th>
      <th>Highest_Score</th>
      <th>Batting_Average</th>
      <th>Balls_Faced</th>
      <th>Batting_Strike_Rate</th>
      <th>Centuries</th>
      <th>...</th>
      <th>Matches_Bowled</th>
      <th>Balls_Bowled</th>
      <th>Runs_Conceded</th>
      <th>Wickets_Taken</th>
      <th>Best_Bowling_Match</th>
      <th>Bowling_Average</th>
      <th>Economy_Rate</th>
      <th>Bowling_Strike_Rate</th>
      <th>Four_Wicket_Hauls</th>
      <th>Five_Wicket_Hauls</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2024-01-01</td>
      <td>Ruturaj Gaikwad</td>
      <td>2</td>
      <td>0</td>
      <td>61</td>
      <td>46</td>
      <td>30.5</td>
      <td>51</td>
      <td>119.61</td>
      <td>0</td>
      <td>...</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2023-01-01</td>
      <td>Ruturaj Gaikwad</td>
      <td>16</td>
      <td>1</td>
      <td>590</td>
      <td>92</td>
      <td>42.14</td>
      <td>400</td>
      <td>147.5</td>
      <td>0</td>
      <td>...</td>
      <td>16</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2022-01-01</td>
      <td>Ruturaj Gaikwad</td>
      <td>14</td>
      <td>0</td>
      <td>368</td>
      <td>99</td>
      <td>26.29</td>
      <td>291</td>
      <td>126.46</td>
      <td>0</td>
      <td>...</td>
      <td>14</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2021-01-01</td>
      <td>Ruturaj Gaikwad</td>
      <td>16</td>
      <td>2</td>
      <td>635</td>
      <td>101</td>
      <td>45.35</td>
      <td>466</td>
      <td>136.26</td>
      <td>1</td>
      <td>...</td>
      <td>16</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2020-01-01</td>
      <td>Ruturaj Gaikwad</td>
      <td>6</td>
      <td>2</td>
      <td>204</td>
      <td>72</td>
      <td>51</td>
      <td>169</td>
      <td>120.71</td>
      <td>0</td>
      <td>...</td>
      <td>6</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>1166</th>
      <td>2023-01-01</td>
      <td>Mayank Markande</td>
      <td>10</td>
      <td>3</td>
      <td>21</td>
      <td>18</td>
      <td>0</td>
      <td>13</td>
      <td>161.54</td>
      <td>0</td>
      <td>...</td>
      <td>10</td>
      <td>228</td>
      <td>300</td>
      <td>12</td>
      <td>4/15</td>
      <td>25.00</td>
      <td>7.89</td>
      <td>19.00</td>
      <td>1</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1167</th>
      <td>2022-01-01</td>
      <td>Mayank Markande</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>2</td>
      <td>42</td>
      <td>57</td>
      <td>1</td>
      <td>1/26</td>
      <td>57.00</td>
      <td>8.14</td>
      <td>42.00</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1168</th>
      <td>2021-01-01</td>
      <td>Mayank Markande</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.00</td>
      <td>0</td>
      <td>0.00</td>
      <td>0</td>
      <td>...</td>
      <td>1</td>
      <td>18</td>
      <td>26</td>
      <td>0</td>
      <td>0/26</td>
      <td>0</td>
      <td>8.66</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1169</th>
      <td>2019-01-01</td>
      <td>Mayank Markande</td>
      <td>3</td>
      <td>1</td>
      <td>6</td>
      <td>6</td>
      <td>6.00</td>
      <td>5</td>
      <td>120.00</td>
      <td>0</td>
      <td>...</td>
      <td>3</td>
      <td>36</td>
      <td>59</td>
      <td>1</td>
      <td>1/23</td>
      <td>59.00</td>
      <td>9.83</td>
      <td>36.00</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>1170</th>
      <td>2018-01-01</td>
      <td>Mayank Markande</td>
      <td>14</td>
      <td>4</td>
      <td>21</td>
      <td>7</td>
      <td>10.50</td>
      <td>24</td>
      <td>87.50</td>
      <td>0</td>
      <td>...</td>
      <td>14</td>
      <td>264</td>
      <td>368</td>
      <td>15</td>
      <td>4/23</td>
      <td>24.53</td>
      <td>8.36</td>
      <td>17.60</td>
      <td>1</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>1130 rows × 25 columns</p>
</div>




```python
columns_to_convert = ['Matches_Batted', 'Not_Outs', 'Runs_Scored', 'Highest_Score',
                      'Centuries', 'Half_Centuries', 'Fours', 'Sixes',
                      'Catches_Taken', 'Matches_Bowled',
                      'Runs_Conceded', 'Wickets_Taken', 'Four_Wicket_Hauls', 'Five_Wicket_Hauls', 'Balls_Faced', 'Balls_Bowled']
```


```python
df[columns_to_convert] = df[columns_to_convert].astype(int)
```


```python
df.columns
```




    Index(['Year', 'Player_Name', 'Matches_Batted', 'Not_Outs', 'Runs_Scored',
           'Highest_Score', 'Batting_Average', 'Balls_Faced',
           'Batting_Strike_Rate', 'Centuries', 'Half_Centuries', 'Fours', 'Sixes',
           'Catches_Taken', 'Stumpings', 'Matches_Bowled', 'Balls_Bowled',
           'Runs_Conceded', 'Wickets_Taken', 'Best_Bowling_Match',
           'Bowling_Average', 'Economy_Rate', 'Bowling_Strike_Rate',
           'Four_Wicket_Hauls', 'Five_Wicket_Hauls'],
          dtype='object')




```python
columns_to_convert1 = ['Batting_Average', 'Batting_Strike_Rate', 'Bowling_Average', 'Economy_Rate', 'Bowling_Strike_Rate']
```


```python
df[columns_to_convert1] = df[columns_to_convert1].astype(float)
```


```python
df.info()
```

    <class 'pandas.core.frame.DataFrame'>
    Int64Index: 1130 entries, 0 to 1170
    Data columns (total 25 columns):
     #   Column               Non-Null Count  Dtype         
    ---  ------               --------------  -----         
     0   Year                 1130 non-null   datetime64[ns]
     1   Player_Name          1130 non-null   object        
     2   Matches_Batted       1130 non-null   int32         
     3   Not_Outs             1130 non-null   int32         
     4   Runs_Scored          1130 non-null   int32         
     5   Highest_Score        1130 non-null   int32         
     6   Batting_Average      1130 non-null   float64       
     7   Balls_Faced          1130 non-null   int32         
     8   Batting_Strike_Rate  1130 non-null   float64       
     9   Centuries            1130 non-null   int32         
     10  Half_Centuries       1130 non-null   int32         
     11  Fours                1130 non-null   int32         
     12  Sixes                1130 non-null   int32         
     13  Catches_Taken        1130 non-null   int32         
     14  Stumpings            1130 non-null   object        
     15  Matches_Bowled       1130 non-null   int32         
     16  Balls_Bowled         1130 non-null   int32         
     17  Runs_Conceded        1130 non-null   int32         
     18  Wickets_Taken        1130 non-null   int32         
     19  Best_Bowling_Match   1130 non-null   object        
     20  Bowling_Average      1130 non-null   float64       
     21  Economy_Rate         1130 non-null   float64       
     22  Bowling_Strike_Rate  1130 non-null   float64       
     23  Four_Wicket_Hauls    1130 non-null   int32         
     24  Five_Wicket_Hauls    1130 non-null   int32         
    dtypes: datetime64[ns](1), float64(5), int32(16), object(3)
    memory usage: 158.9+ KB
    


```python
top_run_scorers = df.sort_values(by='Runs_Scored', ascending=False).head(10)
top_run_scorers
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Year</th>
      <th>Player_Name</th>
      <th>Matches_Batted</th>
      <th>Not_Outs</th>
      <th>Runs_Scored</th>
      <th>Highest_Score</th>
      <th>Batting_Average</th>
      <th>Balls_Faced</th>
      <th>Batting_Strike_Rate</th>
      <th>Centuries</th>
      <th>...</th>
      <th>Matches_Bowled</th>
      <th>Balls_Bowled</th>
      <th>Runs_Conceded</th>
      <th>Wickets_Taken</th>
      <th>Best_Bowling_Match</th>
      <th>Bowling_Average</th>
      <th>Economy_Rate</th>
      <th>Bowling_Strike_Rate</th>
      <th>Four_Wicket_Hauls</th>
      <th>Five_Wicket_Hauls</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>946</th>
      <td>2016-01-01</td>
      <td>Virat Kohli</td>
      <td>16</td>
      <td>4</td>
      <td>973</td>
      <td>113</td>
      <td>81.08</td>
      <td>640</td>
      <td>152.03</td>
      <td>4</td>
      <td>...</td>
      <td>16</td>
      <td>6</td>
      <td>13</td>
      <td>0</td>
      <td>0/13</td>
      <td>0.0</td>
      <td>13.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>223</th>
      <td>2023-01-01</td>
      <td>Shubman Gill</td>
      <td>17</td>
      <td>2</td>
      <td>890</td>
      <td>129</td>
      <td>59.33</td>
      <td>564</td>
      <td>157.80</td>
      <td>3</td>
      <td>...</td>
      <td>17</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>816</th>
      <td>2022-01-01</td>
      <td>Jos Buttler</td>
      <td>17</td>
      <td>2</td>
      <td>863</td>
      <td>116</td>
      <td>57.53</td>
      <td>579</td>
      <td>149.05</td>
      <td>4</td>
      <td>...</td>
      <td>17</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>131</th>
      <td>2016-01-01</td>
      <td>David Warner</td>
      <td>17</td>
      <td>3</td>
      <td>848</td>
      <td>93</td>
      <td>60.57</td>
      <td>560</td>
      <td>151.42</td>
      <td>0</td>
      <td>...</td>
      <td>17</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>268</th>
      <td>2018-01-01</td>
      <td>Kane Williamson</td>
      <td>17</td>
      <td>3</td>
      <td>735</td>
      <td>84</td>
      <td>52.50</td>
      <td>516</td>
      <td>142.44</td>
      <td>0</td>
      <td>...</td>
      <td>17</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>924</th>
      <td>2023-01-01</td>
      <td>Faf du Plessis</td>
      <td>14</td>
      <td>1</td>
      <td>730</td>
      <td>84</td>
      <td>56.15</td>
      <td>475</td>
      <td>153.68</td>
      <td>0</td>
      <td>...</td>
      <td>14</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>129</th>
      <td>2019-01-01</td>
      <td>David Warner</td>
      <td>12</td>
      <td>2</td>
      <td>692</td>
      <td>100</td>
      <td>69.20</td>
      <td>481</td>
      <td>143.86</td>
      <td>1</td>
      <td>...</td>
      <td>12</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>121</th>
      <td>2018-01-01</td>
      <td>Rishabh Pant</td>
      <td>14</td>
      <td>1</td>
      <td>684</td>
      <td>128</td>
      <td>52.61</td>
      <td>394</td>
      <td>173.60</td>
      <td>1</td>
      <td>...</td>
      <td>14</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>5</th>
      <td>2023-01-01</td>
      <td>Devon Conway</td>
      <td>16</td>
      <td>2</td>
      <td>672</td>
      <td>92</td>
      <td>51.69</td>
      <td>481</td>
      <td>139.71</td>
      <td>0</td>
      <td>...</td>
      <td>16</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>471</th>
      <td>2020-01-01</td>
      <td>KL Rahul</td>
      <td>14</td>
      <td>2</td>
      <td>670</td>
      <td>132</td>
      <td>55.83</td>
      <td>518</td>
      <td>129.34</td>
      <td>1</td>
      <td>...</td>
      <td>14</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>10 rows × 25 columns</p>
</div>




```python
import matplotlib.pyplot as plt
import seaborn as sns

# Bar Plot of Top Run Scorers
top_run_scorers = df.sort_values(by='Runs_Scored', ascending=False).head(10)
plt.figure(figsize=(10, 6))
sns.barplot(x='Player_Name', y='Runs_Scored', data=top_run_scorers)
plt.title('Top 10 Run Scorers in IPL')
plt.xlabel('Player')
plt.ylabel('Runs Scored')
plt.xticks(rotation=45)
plt.show()

```


    
![png](output_20_0.png)
    



```python
# Bar Plot of Top Wicket-Takers
top_wicket_takers = df.sort_values(by='Wickets_Taken', ascending=False).head(11)
plt.figure(figsize=(10, 6))
sns.barplot(x='Player_Name', y='Wickets_Taken', data=top_wicket_takers)
plt.title('Top 10 Wicket Takers in IPL')
plt.xlabel('Player')
plt.ylabel('Wickets Taken')
plt.xticks(rotation=45)
plt.show()
```


    
![png](output_21_0.png)
    



```python
import matplotlib.pyplot as plt

# Group the data by player name and sum up the runs scored for each player
player_runs = df.groupby('Player_Name')['Runs_Scored'].sum()

# Sort the players based on their total runs scored and get the top 10 players
top_10_batters = player_runs.sort_values(ascending=False).head(10)

# Plot the top 10 players
plt.figure(figsize=(10, 6))
top_10_batters.plot(kind='bar', color='skyblue')
plt.title('Top 10 Players by Total Runs Scored')
plt.xlabel('Player Name')
plt.ylabel('Total Runs Scored')
plt.xticks(rotation=45, ha='right')
plt.tight_layout()
plt.show()


```


    
![png](output_22_0.png)
    



```python
# Group the data by player name and sum up the runs scored for each player
player_runs = df.groupby('Player_Name')['Wickets_Taken'].sum()

# Sort the players based on their total runs scored and get the top 10 players
top_10_bowlers = player_runs.sort_values(ascending=False).head(10)
print(top_10_bowlers)
# Plot the top 10 players
plt.figure(figsize=(10, 6))
top_10_bowlers.plot(kind='bar', color='red')
plt.title('Top 10 Players by Total Wickets Taken')
plt.xlabel('Player Name')
plt.ylabel('Total Wickets taken')
plt.xticks(rotation=45, ha='right')
plt.tight_layout()
plt.show()
```

    Player_Name
    Yuzvendra Chahal       188
    Piyush Chawla          180
    Amit Mishra            173
    Ravichandran Ashwin    172
    Bhuvneshwar Kumar      170
    Sunil Narine           164
    Ravindra Jadeja        152
    Jasprit Bumrah         148
    Rashid Khan            140
    Umesh Yadav            138
    Name: Wickets_Taken, dtype: int32
    


    
![png](output_23_1.png)
    



```python
import pandas as pd
import matplotlib.pyplot as plt

# Assuming df is your dataframe containing the IPL dataset
# Assuming the dataframe has columns 'Player_Name' and 'Batting_Average' for player names and batting averages

# Step 1: Calculate the total batting average for each player across all years
total_batting_average = df.groupby('Player_Name')['Batting_Average'].sum().reset_index()

# Step 2: Sort the players based on their total batting average
total_batting_average_sorted = total_batting_average.sort_values(by='Batting_Average', ascending=False)

# Step 3: Select the top 10 players with the highest combined batting average
top_10_players = total_batting_average_sorted.head(10)

# Step 4: Plot the combined batting average for these top 10 players
plt.figure(figsize=(10, 6))
plt.bar(top_10_players['Player_Name'], top_10_players['Batting_Average'], color='skyblue')
plt.title('Top 10 IPL Players Based on Combined Batting Average')
plt.xlabel('Player')
plt.ylabel('Combined Batting Average')
plt.xticks(rotation=45, ha='right')
plt.tight_layout()
plt.show()

```


    
![png](output_24_0.png)
    



```python
import pandas as pd
import matplotlib.pyplot as plt

# Assuming df is your dataframe containing the IPL dataset
# Assuming the dataframe has columns 'Player_Name' and 'Batting_Average' for player names and batting averages

# Step 1: Calculate the total batting average for each player across all years
total_batting_average = df.groupby('Player_Name')['Bowling_Average'].sum().reset_index()

# Step 2: Sort the players based on their total batting average
total_batting_average_sorted = total_batting_average.sort_values(by='Bowling_Average', ascending=False)

# Step 3: Select the top 10 players with the highest combined batting average
top_10_players = total_batting_average_sorted.head(10)

# Step 4: Plot the combined batting average for these top 10 players
plt.figure(figsize=(10, 6))
plt.bar(top_10_players['Player_Name'], top_10_players['Bowling_Average'], color='red')
plt.title('Top 10 IPL Players Based on Combined Bowling Average')
plt.xlabel('Player')
plt.ylabel('Combined Bowling Average')
plt.xticks(rotation=45, ha='right')
plt.tight_layout()
plt.show()
```


    
![png](output_25_0.png)
    



```python
# 4. Centuries and Half-Centuries
centuries = df.groupby('Player_Name')['Centuries'].sum().sort_values(ascending=False)[:10]
half_centuries = df.groupby('Player_Name')['Half_Centuries'].sum().sort_values(ascending=False)[:10]
plt.figure(figsize=(12, 6))
plt.subplot(1, 2, 1)
centuries.plot(kind='bar')
plt.title('Centuries Scored by Top 10 Players')
plt.subplot(1, 2, 2)
half_centuries.plot(kind='bar')
plt.title('Half-Centuries Scored by Top 10 Players')
plt.tight_layout()
plt.show()

```


    
![png](output_26_0.png)
    



```python
# 2. Total Wickets Taken
total_wickets = df.groupby('Player_Name')['Wickets_Taken'].sum().sort_values(ascending=False)[:10]
plt.figure(figsize=(10, 6))
total_wickets.plot(kind='bar')
plt.xlabel('Player')
plt.ylabel('Total Wickets Taken')
plt.title('Total Wickets Taken by Top 10 Bowlers')
plt.show()






```


    
![png](output_27_0.png)
    



```python
# 3. Economy Rate Comparison
economy_rate = df.groupby('Player_Name')['Economy_Rate'].mean().sort_values(ascending=False)[:10]
plt.figure(figsize=(10, 6))
economy_rate.plot(kind='bar')
plt.xlabel('Player')
plt.ylabel('Economy Rate')
plt.title('Economy Rate Comparison of Top 10 Bowlers')
plt.show()
```


    
![png](output_28_0.png)
    



```python
# 4. 5-Wicket Hauls
five_wicket_hauls = df.groupby('Player_Name')['Five_Wicket_Hauls'].sum().sort_values(ascending=False)[:10]
plt.figure(figsize=(10, 6))
five_wicket_hauls.plot(kind='bar')
plt.xlabel('Player')
plt.ylabel('5-Wicket Hauls')
plt.title('5-Wicket Hauls by Top 10 Bowlers')
plt.show()
```


    
![png](output_29_0.png)
    



```python
# Group by player name and calculate the mean of batting averages
avg_batting_by_player = df.groupby('Player_Name')['Batting_Average'].mean().reset_index()
avg_batting_by_player = avg_batting_by_player.sort_values(by='Batting_Average', ascending=False).head(10)
print(avg_batting_by_player)
# Visualize batting average
plt.figure(figsize=(10, 6))
plt.bar(avg_batting_by_player['Player_Name'], avg_batting_by_player['Batting_Average'], color='skyblue')
plt.title('Average Batting Average of Players')
plt.xlabel('Player')
plt.ylabel('Average Batting Average')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```

              Player_Name  Batting_Average
    38       Devon Conway        46.845000
    25   B. Sai Sudharsan        44.320000
    66           KL Rahul        43.098182
    128   Rachin Ravindra        41.500000
    119         Phil Salt        40.625000
    33       David Warner        40.076667
    151   Ruturaj Gaikwad        39.056000
    82           MS Dhoni        38.920000
    194       Virat Kohli        38.112941
    183        Tom Curran        37.220000
    


    
![png](output_30_1.png)
    



```python
# Group by player name and calculate the mean of batting averages
avg_bowling_by_player = df.groupby('Player_Name')['Bowling_Average'].mean().reset_index()
avg_bowling_by_player = avg_bowling_by_player.sort_values(by='Bowling_Average', ascending=False).head(10)
print(avg_bowling_by_player)

# Visualize bowling average
plt.figure(figsize=(10, 6))
plt.bar(avg_bowling_by_player['Player_Name'], avg_bowling_by_player['Bowling_Average'], color='red')
plt.title('Average Bowling Average of Players')
plt.xlabel('Player')
plt.ylabel('Average Bowling Average')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```

                Player_Name  Bowling_Average
    72   Krishnappa Gowtham        67.498000
    70         Kartik Tyagi        60.692500
    34         David Willey        51.500000
    146        Rishi Dhawan        51.095000
    7            Akash Deep        50.000000
    80      Lockie Ferguson        49.328333
    110        Nathan Ellis        47.470000
    105        Mukesh Kumar        46.570000
    200          Yash Dayal        44.970000
    123     Prasidh Krishna        43.900000
    


    
![png](output_31_1.png)
    



```python
import matplotlib.pyplot as plt

# Scatter plot of actual vs. predicted batting averages
plt.figure(figsize=(8, 6))
# Training set
plt.scatter(y_train_bowling, model_bowling.predict(X_train_bowling), color='blue', label='Training Set')
# Testing set
plt.scatter(y_test_bowling, y_pred_bowling, color='red', label='Testing Set')
#plt.plot([min(y_test), max(y_test)], [min(y_test), max(y_test)], color='red', linestyle='--')
plt.xlabel('Actual Batting Average')
plt.ylabel('Predicted Batting Average')
plt.title('Actual vs. Predicted Batting Averages')
plt.show()

```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[100], line 6
          4 plt.figure(figsize=(8, 6))
          5 # Training set
    ----> 6 plt.scatter(y_train_bowling, model_bowling.predict(X_train_bowling), color='blue', label='Training Set')
          7 # Testing set
          8 plt.scatter(y_test_bowling, y_pred_bowling, color='red', label='Testing Set')
    

    NameError: name 'y_train_bowling' is not defined



    <Figure size 800x600 with 0 Axes>



```python
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

# Define features (X) and target variable (y) for bowling averages
X_bowling = df[['Matches_Batted', 'Not_Outs', 'Runs_Scored', 'Balls_Faced', 'Batting_Strike_Rate', 
                     'Matches_Bowled', 'Balls_Bowled', 'Runs_Conceded', 'Wickets_Taken']]
y_bowling = df['Bowling_Average']

# Split the data into training and testing sets for bowling averages (80% train, 20% test)
X_train_bowling, X_test_bowling, y_train_bowling, y_test_bowling = train_test_split(X_bowling, y_bowling, test_size=0.2, random_state=42)

# Initialize and train the regression model for bowling averages
model_bowling = LinearRegression()
model_bowling.fit(X_train_bowling, y_train_bowling)

# Predict bowling averages on the testing set
y_pred_bowling = model_bowling.predict(X_test_bowling)

# Evaluate the model using Mean Squared Error (MSE) for bowling averages
mse_bowling = mean_squared_error(y_test_bowling, y_pred_bowling)
print("Mean Squared Error for Bowling Average:", mse_bowling)

# Interpret model coefficients for bowling averages
coefficients_bowling = pd.DataFrame(model_bowling.coef_, X_bowling.columns, columns=['Coefficient'])
print("Model Coefficients for Bowling Average:")
print(coefficients_bowling)

```

    Mean Squared Error for Bowling Average: 263.9390346574175
    Model Coefficients for Bowling Average:
                         Coefficient
    Matches_Batted         -3.049689
    Not_Outs               -0.211360
    Runs_Scored             0.051791
    Balls_Faced            -0.084634
    Batting_Strike_Rate    -0.029443
    Matches_Bowled          2.708895
    Balls_Bowled           -0.082090
    Runs_Conceded           0.284459
    Wickets_Taken          -3.908242
    


```python
plt.figure(figsize=(10, 5))

# Training set
plt.scatter(y_train_bowling, model_bowling.predict(X_train_bowling), color='blue', label='Training Set')
# Testing set
plt.scatter(y_test_bowling, y_pred_bowling, color='skyblue', label='Testing Set')

plt.title('Scatter Plot for Bowling Averages')
plt.xlabel('True Bowling Averages')
plt.ylabel('Predicted Bowling Averages')
plt.legend()
plt.grid(True)
plt.show()
```


    
![png](output_34_0.png)
    



```python
# 1. Prepare the Data
# Assuming your dataset is already prepared and loaded into a pandas DataFrame called 'df'

# 2. Split the Data
# Split the dataset into features (X) and target variable (y)
X = df[['Matches_Batted', 'Not_Outs', 'Runs_Scored', 'Balls_Faced', 'Batting_Strike_Rate', 'Centuries', 'Half_Centuries', 'Fours', 'Sixes', 'Catches_Taken', 'Stumpings', 'Matches_Bowled', 'Balls_Bowled', 'Runs_Conceded', 'Wickets_Taken', 'Bowling_Average', 'Economy_Rate', 'Bowling_Strike_Rate', 'Four_Wicket_Hauls', 'Five_Wicket_Hauls']]
y = df['Batting_Average']  # Target variable

# 3. Split the Data
from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# 4. Choose a Model
from sklearn.linear_model import LinearRegression
model = LinearRegression()  # Initialize the linear regression model

# 5. Train the Model
model.fit(X_train, y_train)

# 6. Evaluate the Model
from sklearn.metrics import mean_squared_error, r2_score
y_pred = model.predict(X_test)
mse = mean_squared_error(y_test, y_pred)
r2 = r2_score(y_test, y_pred)
print("Mean Squared Error:", mse)
print("R-squared:", r2)

# 7. Make Predictions
# You can make predictions on new data if available

# 8. Visualize the Results (optional)
# You can visualize the actual vs predicted values to assess the model's performance

```

    Mean Squared Error: 85.56469711725279
    R-squared: 0.7024406207198313
    


```python
import matplotlib.pyplot as plt

# Plotting the actual vs predicted values
plt.figure(figsize=(10, 6))
#plt.scatter(y_test, y_pred, color='blue', label='Actual vs Predicted')
# Training set
plt.scatter(y_train_bowling, model_bowling.predict(X_train_bowling), color='black', label='Training Set')
# Testing set
plt.scatter(y_test_bowling, y_pred_bowling, color='green', label='Testing Set')
plt.plot([min(y_test), max(y_test)], [min(y_test), max(y_test)], color='red', linestyle='--', label='Perfect Prediction')
plt.title('Actual vs Predicted Batting Averages')
plt.xlabel('Actual Batting Average')
plt.ylabel('Predicted Batting Average')
plt.legend()
plt.grid(True)
plt.show()

```


    
![png](output_36_0.png)
    



```python
import matplotlib.pyplot as plt

# Filter the dataframe to include only data for the top 10 batters
top_10_players = df.groupby('Player_Name')['Batting_Average'].mean().nlargest(5)
top_10_players_data = df[df['Player_Name'].isin(top_10_players.index)]

# Plotting the data
plt.figure(figsize=(10, 6))
for player, data in top_10_players_data.groupby('Player_Name'):
    plt.plot(data['Year'], data['Batting_Average'], marker='o', linestyle='-', label=player)

plt.title('Batting Average Over the Years for Top 10 Batters')
plt.xlabel('Year')
plt.ylabel('Batting Average')
plt.legend()
plt.grid(True)
plt.show()

```


    
![png](output_37_0.png)
    



```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

# Assuming df is your dataframe with the relevant columns

# Step 1: Filter the dataset for top 10 players based on batting averages
top_10_players = df.groupby('Player_Name')['Batting_Average'].mean().nlargest(10).index
top_10_data = df[df['Player_Name'].isin(top_10_players)]

# Step 2: Group the data by player and calculate highest score
player_highest_score = top_10_data.groupby('Player_Name')['Highest_Score'].max()

# Step 3: Prepare data for regression
X = player_highest_score.values.reshape(-1, 1)  # Feature: Highest Score
y = top_10_data.groupby('Player_Name')['Batting_Average'].mean().values  # Target: Batting Average

# Step 4: Split the data into training and testing sets
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Step 5: Choose a regression model (Linear Regression)
model = LinearRegression()

# Step 6: Train the regression model
model.fit(X_train, y_train)

# Step 7: Evaluate the model's performance
train_rmse = mean_squared_error(y_train, model.predict(X_train), squared=False)
test_rmse = mean_squared_error(y_test, model.predict(X_test), squared=False)

print("Train RMSE:", train_rmse)
print("Test RMSE:", test_rmse)

# Step 8: Make predictions
predictions = model.predict(X_test)

```

    Train RMSE: 2.8263395988021083
    Test RMSE: 3.2153172604830567
    


```python
# Group by player name and calculate the mean of batting averages
avg_batting_by_player = df.groupby('Player_Name')['Batting_Average'].mean().reset_index()

# Visualize batting average
plt.figure(figsize=(10, 6))
plt.bar(avg_batting_by_player['Player_Name'], avg_batting_by_player['Batting_Average'], color='skyblue')
plt.title('Average Batting Average of Players')
plt.xlabel('Player')
plt.ylabel('Average Batting Average')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```


    
![png](output_39_0.png)
    



```python
# Assuming you have a DataFrame named 'bowling_data' with columns 'Runs_Conceded' and 'Balls_Bowled'

# Calculate total runs conceded by each bowler
total_runs_conceded = df.groupby('Player_Name')['Runs_Conceded'].sum()

# Calculate total overs bowled by each bowler
total_overs_bowled = df.groupby('Player_Name')['Balls_Bowled'].sum() / 6  # Convert balls to overs

# Calculate economy rate for each bowler
economy_rate = total_runs_conceded / total_overs_bowled

# Add economy rate to DataFrame
df['Economy_Rate'] = df['Player_Name'].map(economy_rate)
print(df['Economy_Rate'])

# Now 'bowling_data' DataFrame contains the economy rate for each bowler
```

    0            NaN
    1            NaN
    2            NaN
    3            NaN
    4            NaN
              ...   
    1166    8.323529
    1167    8.323529
    1168    8.323529
    1169    8.323529
    1170    8.323529
    Name: Economy_Rate, Length: 1130, dtype: float64
    


```python
# Filter out NaN values
economy_rate = economy_rate.dropna()

# Sort the bowlers by economy rate
top_bowlers = economy_rate.sort_values().head(10) 
print(top_bowlers)
```

    Player_Name
    Ajinkya Rahane      5.000000
    Ayush Badoni        5.368421
    Prashant Solanki    6.333333
    N. Tilak Varma      6.666667
    Rashid Khan         6.688897
    Sunil Narine        6.719363
    Gerald Coetzee      6.750000
    Jayant Yadav        6.846154
    Mitchell Santner    6.884615
    Moeen Ali           6.946479
    dtype: float64
    


```python
# Plotting the top bowlers based on economy rate
plt.figure(figsize=(10, 6))
top_bowlers.plot(kind='bar', color='red')
plt.title('Top Bowlers based on Bowing Average')
plt.xlabel('Player Name')
plt.ylabel('Bowling Average')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```


    
![png](output_42_0.png)
    



```python
import pandas as pd

# Assuming you have a DataFrame named 'bowling_data' with columns 'Runs_Conceded' and 'Wickets_Taken'

# Calculate total runs conceded by each bowler
total_runs_conceded = df.groupby('Player_Name')['Runs_Conceded'].sum()

# Calculate total wickets taken by each bowler
total_wickets_taken = df.groupby('Player_Name')['Wickets_Taken'].sum()

# Calculate bowling average for each bowler
bowling_average = total_runs_conceded / total_wickets_taken

# Add bowling average to DataFrame
df['Bowling_Average'] = df['Player_Name'].map(bowling_average)
df['Bowling_Average']
# Now 'bowling_data' DataFrame contains the bowling average for each bowler

```




    0             NaN
    1             NaN
    2             NaN
    3             NaN
    4             NaN
              ...    
    1166    27.387097
    1167    27.387097
    1168    27.387097
    1169    27.387097
    1170    27.387097
    Name: Bowling_Average, Length: 1130, dtype: float64




```python
# Filter out NaN values
bowling_average = bowling_average.dropna()

# Sort the bowlers by bowling average
top_bowlers = bowling_average.sort_values().head(10)  # Select top 10 bowlers
```


```python
import matplotlib.pyplot as plt

# Assuming you have obtained the top bowlers Series named 'top_bowlers'

# Plotting the top bowlers based on bowling average
plt.figure(figsize=(10, 6))
top_bowlers.plot(kind='bar', color='green')
plt.title('Top Bowlers based on Bowling Average')
plt.xlabel('Player Name')
plt.ylabel('Bowling Average')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()

```


    
![png](output_45_0.png)
    



```python

```
