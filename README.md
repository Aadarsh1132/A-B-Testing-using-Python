# A-B-Testing-using-Python
A/B Testing means analyzing two marketing strategies to choose the best marketing strategy that can convert more traffic into sales (or more traffic into your desired goal) effectively and efficiently.
In A/B testing, we analyze the results of two marketing strategies to choose the best one for future marketing campaigns.For example: 1)An online retailer might test different product descriptions to see which one leads to more sales.
2) A digital advertising campaign might test different ad copy to see which version results in a higher click-through rate.

Your goal can be to boost sales, followers, or traffic, but when we choose the best marketing strategy according to the results of our previous marketing campaigns, it is nothing but A/B testing.

For the task of A/B testing, we need to have a dataset about two different marketing strategies for the same goal.

The dataset we are using here contains two data files about two marketing campaigns (Control Campaign and Test Campaign).

# A/B Testing to Find the Best Marketing Strategy

## We will first analyze the relationship between the number of impressions we got from both campaigns and the amount spent on both campaigns:
![newplot](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/5026eec4-a76f-4de2-8bc9-d232fe88dbe4)
The control campaign resulted in more impressions according to the amount spent on both campaigns.

## Now let’s have a look at the number of searches performed on the website from both campaigns:
![newplot (1)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/72cebfc6-3902-4dfd-aef1-5f550636bab7)
The test campaign resulted in more searches on the website.

##  Let’s have a look at the number of website clicks from both campaigns:
![newplot (2)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/0790f480-773f-4a1a-bd8f-c8c81cf92b6a)
The test campaign wins in the number of website clicks.

## Now let’s have a look at the amount of content viewed after reaching the website from both campaigns:
![newplot (3)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/d68daf5c-31a6-41dd-b0aa-2e57dc79eb86)
The audience of the control campaign viewed more content than the test campaign. Although there is not much difference, as the website clicks of the control campaign were low, its engagement on the website is higher than the test campaign.

## Now let’s have a look at the number of products added to the cart from both campaigns:
![newplot (4)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/b28101b9-48d2-43e5-a502-8d1a6ffee8f5)
Despite low website clicks more products were added to the cart from the control campaign.

## Now let’s have a look at the amount spent on both campaigns:
![newplot (5)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/7bcf9ec6-aec6-42b9-ba1a-d514f7b48a81)
The amount spent on the test campaign is higher than the control campaign. But as we can see that the control campaign resulted in more content views and more products in the cart, the control campaign is more efficient than the test campaign.

## Now let’s have a look at the purchases made by both campaigns:
![newplot (6)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/1e7bbde4-21de-454a-84eb-ac4a676dfae9)
There’s only a difference of around 1% in the purchases made from both ad campaigns. As the Control campaign resulted in more sales in less amount spent on marketing, the control campaign wins here!

## Now let’s analyze some metrics to find which ad campaign converts more. We will first look at the relationship between the number of website clicks and content viewed from both campaigns:
![newplot (7)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/8b7a7163-8ec5-45dc-9fdd-546902cec2fb)
The website clicks are higher in the test campaign, but the engagement from website clicks is higher in the control campaign. So the control campaign wins!


## Now we will analyze the relationship between the amount of content viewed and the number of products added to the cart from both campaigns:
![newplot (8)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/3427b413-cb07-402b-9ae8-e32aca331dab)
Again, the control campaign wins!

##  Let’s have a look at the relationship between the number of products added to the cart and the number of sales from both campaigns:
![newplot (9)](https://github.com/Aadarsh1132/Supply-Chain-Analysis/assets/133105879/4fcc2b55-153c-4cc5-b439-4126c5d95da4)
Although the control campaign resulted in more sales and more products in the cart, the conversation rate of the test campaign is higher.

# Conclusion
From the above A/B tests, we found that the control campaign resulted in more sales and engagement from the visitors. More products were viewed from the control campaign, resulting in more products in the cart and more sales. But the conversation rate of products in the cart is higher in the test campaign. The test campaign resulted in more sales according to the products viewed and added to the cart. And the control campaign results in more sales overall. So, the Test campaign can be used to market a specific product to a specific audience, and the Control campaign can be used to market multiple products to a wider audience.




