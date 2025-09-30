How to Add Custom Fonts in Your Shopify Store?

1. Download font which you want to apply.

2. Go to Content -> Files -> Upload files

3. Go to themes -> Edit code -> Sections

4. Create new section and name it ‘custom-font’ and paste below code:

5. include the 'custom-font.liquid' section in the body tag in 'theme.liquid' (find it in layout directory). Find <body> and paste below line:
   {% section 'custom-font' %}
6. Now you can find a new setting section to the page "Custom Font" link the font url and customse other options.

Soruce: https://www.youtube.com/watch?v=sBKE_M-I4pY
