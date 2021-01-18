# Day-2
__01/12/20__

## What are the three types of relationships?

The first type of relationship is one to one. An example is a person and their phone number. One person has that phone number and that phone number only has one person attached to it. The second type is one to many. An example would be a blog post and its comments. The blog post has many comments, but the comments only belong to one blog. The last relationship is many to many. An example of this is a classroom and its students. The students have multiple classrooms and the classrooms contain multiple students.

## What are the benefits of the traditional linking of relationships instead of embedding?

One benefit is that the size of the parent will not change as children are added. Another benifit is the ability to return paginated children. This allows you to make multiple pages instead of displaying all of the children at once. 

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive you decision on how to create it?

If we use queries, we must perform two queries in both directions. This becomes impractical if we have thousands on one side. If we use one way embedding, we can easily break the 16mb max document size. The most effective way would be third collection embedding. This allows you to keep just a record of the relationships