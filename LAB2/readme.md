For the second problem (in#1) I didn’t need to use a subquery to retrieve the info you were looking for. I thought it would just be cleaner and easier to do it this way. 


## LAB 2
__________
The topic of my data base will be commercial/homebrewing

The purpose of the data base will be to list beer style, region, fermentable, adjuncts and yeast. For easy cross-referencing materials and ingredients for styles of beer from certain regions. As far as security I will start by using GRANT and CREATE ROLE statements to control the amount of access to the data base from admins to users. By using the GRANT statements. I can monitor who has what access with SHOW GRANTS statements and control excessive use or change admins with REVOKE and GRANTS or assign someone a ROLE. I may also need to use an SSL system to encrypt data because users will be outside the local network. 

The tables will start off with Ingredients, adjuncts, style, and yeast. 
The ingredients table will contain fermentable ingredients such as the grains and barley. The column names of the ingredients could contain malted barley, wheat, maize(corn) and rice. Each of the column will contain a list of different products pertaining to that category of column. 

For the adjuncts table the column names could consist of hops, fruits/vegetables, Unmalted barley and herbs/spices. The data for each of these columns are almost endless so I will pick about 10-15 of the most popular for each column. 

The Style table will be built around the four main style. Ales, Lagers, stout/porter, and German. Each of these column or types have hundreds of sub styles but like the adjuncts I will keep to the top 10 for each column or style. 

The Yeast table will contain rows that correspond closely the style table. Because each style has a yeast stain that goes with it. There are thousands of yeast stains and hundreds of categories of yeast but like the others I will keep it to the Four main categories and 10 of the top in each column. 
