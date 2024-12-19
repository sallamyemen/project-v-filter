WHAT TO DO
At the moment, we have the old website for PV, but we need to have all of our websites in one of the latest technology in the market. 

As far as we do not have a new design ready, we should start the development of functionality where the design is not that much important, so do not focus on the design.

 

Remake the catalog logic in a new project https://projectvint.ru/catalog/ 

LOGIC
The logic may be the same as it is on the website already:

For each single category we have a route for that; e.g. https://projectvint.ru/catalog/category-nutraceuticals/ -> https://projectvint.ru/catalog/nutraceuticals/ (make note I have deleted the word category)
For each single subcategory we have a route for that; e.g. https://projectvint.ru/catalog/category-nutraceuticals/collection-classic-hit/ -> https://projectvint.ru/catalog/nutraceuticals/collection-classic-hit/  (make note I have deleted the word category)
If more than two subcategories are selected, then we redirect to the main catalog, and set to the url the new parameters; e.g. https://projectvint.ru/catalog/?category=nutraceuticals,cosmeceuticals&collection=classic-hit,direct-hit,switzerland-cosmetics -> https://projectvint.ru/catalog/?category=nutraceuticals,cosmeceuticals&collection=classic-hit,direct-hit,switzerland-cosmetics -> https://projectvint.ru/catalog/?categories=nutraceuticals,cosmeceuticals&collections=classic-hit,direct-hit,switzerland-cosmetics  (make note I have change the parameter names)
Do not forget to cover the cases where the use arrives to the catalog with already some parameters in the URL, in this case the catalog filters should be set automatically from there;
