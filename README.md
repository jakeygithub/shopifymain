# Shopify Themes

You can compare the code for various free Shopify themes.

Name | Branch
--- | ---
Debut | [t_debut](https://github.com/trkin/shopify-themes/tree/t_debut)
Simple | [t_debut](https://github.com/trkin/shopify-themes/tree/t_simple)
Brooklyn | [t_debut](https://github.com/trkin/shopify-themes/tree/t_brooklyn)

Demo store you can find on <https://trk-themes.myshopify.com/>

# Developing

After you create development store, you need to create private app and obtain
password and access with themekit. Here is example of config.yml

~~~
development:
  password: shppa_bb123...123
  # theme_id: "99870998695" # Debut
  # theme_id: 100071768231 # Brooklyn
  theme_id: 100071800999 # Simple
  store: trk-themes.myshopify.com
~~~

Note that `config.yml` is git ignored since we do not want to commit to
repository.
