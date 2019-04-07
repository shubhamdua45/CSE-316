You have been hired by Larsen and Toubro Limited to automate the flow of traffic on a onelane bridge that has been the site of numerous collisions. L and T Limited wants you to
implement the following rules:
• Traffic can flow in only a single direction on the bridge at a time.
• Any number of cars can be on the bridge at the same time, as long as they are all traveling
in the same direction.
• To avoid starvation, you must implement the “five car rule”: once 5 or more consecutive
northbound cars have entered the bridge, if there are any southbound cars waiting then no
more northbound cars may enter the bridge until some southbound cars have crossed. A
similar rule also applies once 5 or more consecutive southbound cars have entered the
bridge.
