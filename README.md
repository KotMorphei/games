# games

Проект по анализу данных, написаный на python. 

Ноутбук с непосредственно кодом находится в файле games.ipynb. Файл с исходными данными для анализа - games.csv.



stop = stopwords.words('russian') df['product_lem'] = df['product'].apply(lambda x: ' '.join( [word for word in x.split() if word not in (stop)])) df['product_lem'].head()


