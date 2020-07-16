# 1. Problem
when you want to add a new addon

![new addon](https://i.imgur.com/EFoEKzd.png)

the default value is 'New Addon'; which, requires that you first clear this value before setting your own. This wastes time.

# 2. Solution

The default values are maintained, but logic is added to 'editModal' to ignore the default values and instead have a label that has no value when edited.

As you can see the defaulted values shows the value grayed out  
![new values](https://i.imgur.com/8wEZXjC.png)

if you click on either, the modal is now blank  
![new modal](https://i.imgur.com/rU9LMNC.png)
