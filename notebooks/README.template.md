##  COVID-19 {{ date }} report
Feel free to use these charts to raise awareness about the danger Covid-19 represents. 

### Spread comparison 
Coronavirus is spreading differently in different countries.

Spain is very concerning, it takes less than two days for death count to double. Faster than Italy.

UK is starting after other countries, so death count is smaller, but growth is even faster than Spain.

France is following quite accurately Italy.


![Covid-19 Chart for {{main_chart_countries}}]({{url_prefix}}_main_comparison.png "Covid-19 Chart for {{main_chart_countries}}")

### Most Affected Countries as of {{date}}
{% for country in most_impacted_countries_data %}
[{{country.name }}](countries/{{country.path}})
{% endfor %}

### Other Affected Countries
{% for country in other_countries_data %}
[{{country.name }}](countries/{{country.path}})
{% endfor %}