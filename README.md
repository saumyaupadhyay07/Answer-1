# Answer-1
FrontEnd Scenarios:
1.User should be able to add new item to the inventory.
2. New item should contain below mentioned columns:
Name
Desription
Price
3. User should be able to upload tumbnail (picture)of the item in case if application supports image uploads
4. User should be able to remove the item from the inventory.
5. if user clicks on an item then it should redirect new page and new page should have al the details- name, description, price, and optionally photo.
6. Page should support both horizontal and vertical visual styles.
7. If user navigates between the 2 pages then full-page reload might occur.

BackEnd Scenarios:
1. Store's inventory should be persistent in case of restarting  of backend system.and it will use sql DB in case of persistent data storage is required.
2. Each and every Front-end function calls API request (different API calls as per the fron-end function)
3. all API calls should be asynchronus.

Automtion criteria:
all the test case can be automated.sometimes it will be difficult to deal with persistent data.
