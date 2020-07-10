# 1. Problem

"  
When a partner logs on and makes edits to their menu, it would be nice if we got a notification somehow. Right now, we dont know when partners make edits and I regularly come across mistakes they have made (multiple empty categories name "New Product Category" or alcohol being secretly added to a menu)  
"


# 2. Solution
This can be done by having a server side process that listens for certain events and alerts the admins when one occurs; for example one event could be 'edits saved' which will alert all admins immediately. This can be further optimized with filters to only announce events with certain criteria.
