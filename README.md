1. Create new post, 
2. Can view all the posts, 
3. Can comments to any specific post
4. Can moderate any post enum {'PENDING','REJECTED','APPROVED'}
5. Event Bus to handle all the events and send it to all the services
6. Query to get all the posts without depending on posts and comments services
7. Every service is using seperate DB and connected through Event bus
