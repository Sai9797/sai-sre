---
Title: Mini project reflection
Date: 2023-04-25
---

<h1>Skills from the learning language I utilized to work on mini project</h1>

- Use of static keyword: The code uses the static keyword to define the "pantry" and "recipes" Maps as static members of the "SmartFridgeContents" class. This means that the Maps can be accessed without creating an instance of the class.
- Initialization of a HashMap: The code demonstrates how to initialize a HashMap using an anonymous inner class in Java. It defines a static Map called "pantry" that maps ingredients to their quantities, and another static Map called "recipes" that maps recipe names to a nested Map of ingredients and their quantities.

<h1>Additional skills/knowledge I had learned to complete the tasks</h1>

- I have learned about Nested HashMap and its implementation
- The mini project utilized nested HashMaps. The "recipes" Map has String keys for recipe names and maps them to a nested Map that maps ingredients to their quantities.
- Also, I have learned how to collaborate with team members to complete the tasks in the given time framework.

<h1>Challenges faced</h1>

-  A challenge I faced when using HashMaps is overwriting values. If a new value is put into a HashMap with the same key as an existing value, the existing value is overriden. This can be a problem if the existing value is needed and should not be replaced. To avoid this, I have learned to check if a key already exists in the HashMap before adding a new value with that key.
-  Another challenge that is hash collisions. A hash collision happens when two different keys have the same hash code, causing them to map to the same bucket in the HashMap. This can lead to incorrect values being retrieved from the HashMap or slower performance. To avoid this I learned to use a good hashing function and to make sure that the hashCode() and equals() methods are implemented correctly for the key objects.

<h1>Codeblocks</h1>

- https://github.com/SLUSE-Spring2022/miniproject-java/blob/main/SmartFridgeContents.java
- https://github.com/SLUSE-Spring2022/miniproject-java/blob/main/SmartFridgeProgram.java
