# Avocado Transportation Optimization

## Authors
Tz-Ruei Liu (tliu292@wisc.edu)  
Hashim Hussain Aljarrash (aljarrash@wisc.edu)  
Zhenyu Zou (zzou24@wisc.edu)

## Introduction

Avocados are stone fruit that grow in warm temperature. They have many health benefits; for instance, avocados are a great source of vitamins, including Vitamin C, E, K, and B-5, as well as nicain, magnesium, etc [[1](https://www.medicalnewstoday.com/articles/270406)]. For many US restaurants, avocados are very popular ingredients. There are even avocado-themed restaurants all over the states. Avocado Grill, a resturant located in West Palm Beach, Florida, is a popular avocado-themed restaurant. Its menu includes dishes like avocado vinaigrette and grilled avocado wedges; virtually all food in the menu uses avocado as the main ingredient [[2](https://www.rd.com/advice/travel/avocado-themed-restaurants/)]. Our team is also a big fan of avocados, so we were wondering how to apply the optimization models we learnt in class to this delicious food. 

This project, Avocado Transportation Optimization, aims to determine an optimal route of delivering avocado to restaurants that use avocados as their primary ingredient, while minimizing the total cost, including the cost of purchasing avocados and the cost of transportation from various locations.

We start with a simple problem and expand the scale of the problem as we dive in. At the beginning phase, we suppose that our client only wants to open two restaurants in Madison, Wisconsin and Chicago, Illinois that heavily use avocado. We also restrict suppliers from nearby states. We would like to find where and how many avocados to import to the restaurants that minimizes the total cost.

Next, we no longer restrict importing to nearby states and assume that suppliers are located all over the states. Again, we would like to find the minimum cost from suppliers to the two given restaurants.

Then, we would add a time constraint and propose that the restaurants would like to import avocado in every fixed interval. For instance, real-life restaurants might need to import avocados at least once per month to make sure that avocados are fresh and can be delivered to the customers.

Last but not least, it is also interesting to see where to open the restaurants that minimize the total cost, if the client did not decide the restaurant locations yet.

This report will walk the client through many iterations of the problem, with increasing complexity, in order to provide guidance for restaurants on how to import avocado from the cheapest locations. This model can also be applied to restaurants that use other food ingredients, not only avocados.
