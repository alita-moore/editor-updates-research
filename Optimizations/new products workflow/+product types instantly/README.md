# 1. Problem
When you want to create a new product (either via the new, from old, or template options) the following work flow is observed:

First you click one of the options  
![click the new product](https://i.imgur.com/1zN9xL2.png)

If you're choosing to base your new product off of a template or old menu item you get a drop down menu

![dropdown popup](https://i.imgur.com/UBMOCQT.png)
![click item](https://i.imgur.com/fyWsbCK.png)

After selecitng your product you then have to click the product in the main menu, then click edit in the editor, and then finally click the 'Name' box:

![click product](https://i.imgur.com/8AWpl2e.png)
![edit](https://i.imgur.com/9M9SCcQ.png)
![select the name box](https://i.imgur.com/BCA0lFS.png)

Clearly, this process is non-optimal. So, the goal here is to optimize the process for all of the three possible options.

# 2. Solution

There're a couple simple optimizations:

- the dropdown opens automatically
- once a product is clicked it goes immediately through to the name category
