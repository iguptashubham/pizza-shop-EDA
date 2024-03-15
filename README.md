# Pizza-shop-EDA
**Pizza Shop** - satisfying late-night cravings and fueling game nights for over 20 years. Our reputation is built on fresh, local ingredients – you can practically taste the difference in every bite. We crank out classic New York-style pizzas with that perfect thin crust, but don't be afraid to get adventurous! Our menu has something for everyone, from veggie-lovers to meat-eaters, with some seriously unique combos you won't find anywhere else. Come hungry, leave happy – that's the Luigi's promise.
![-data-analysis-by--- (1)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/bddb857c-4112-4be1-b1d6-a65ecf64abd1)
## Pizza Shop Peaks Hours
<p><code>df['hour'].value_counts().sort_index(ascending = True).plot(kind = 'bar', figsize = (10,5), edgecolor='black', color = '#fc6358', width = 0.7)
plt.title('Pizza Shop Peak Hours')
plt.xlabel('Hour')
plt.xticks(rotation = 0)
plt.yticks([])
mean_value = df['hour'].value_counts().values.mean()
plt.axhline(y=mean_value, color='grey', linestyle='--', label='Mean')
plt.text(14,3500,'Average customers', color='black', ha='right', fontweight = 'book')
plt.show()</code>.</p>

![download (4)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/345b37a4-75fe-46a8-b43b-eefeeb72c207)

## Wordcloud
#### made by python library
### Pizza wordcloud
![download (1)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/2c645087-f4b2-4ceb-94fb-7a1759c7673c)
### Ingredients wordcloud
![download (2)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/1047a8e2-f25f-46fe-b0f4-4d0909701340)

![download (5)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/25134eb8-bf00-4550-a978-09a15a7ee5e0)
![download (6)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/cdb6a25c-d020-44f7-8217-fe1bd62e70b4)
![download (7)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/738f1f3a-c5c3-4bbb-b6f7-ca99ede226d3)
![download (8)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/e4bf5542-b816-4c2d-be72-ea5acc468853)
![download](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/b00f9798-b449-4f1f-894d-393d127160a1)
![download (3)](https://github.com/iguptashubham/pizza-shop-EDA/assets/140319219/04c88e0f-d5a9-438b-aab5-070917c6fe7b)
