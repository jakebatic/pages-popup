CMS Setup:

1. Create a new navigation named **Development Menu**
2. Ensure the handle for this navigation menu remains **development-menu**
3. Add all of the pages/products/collections/blog you're building out as items to this navigation

Code Setup:

1. Create snippet called **pages-popup**
2. Add the popup content code
3. In the **theme.liquid** file locate the **<body>** tag
4. Add {% render 'pages-popup' %} just below the **<body>** tag
   
DONE!
