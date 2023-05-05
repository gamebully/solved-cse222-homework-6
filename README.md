Download Link: https://assignmentchef.com/product/solved-cse222-homework-6
<br>
Design and implement an e-shopping application that has two user roles as usual: traders and customers. Users authenticate to the system by using their <em>user IDs</em> and <em>passwords</em>. The user ID is an eight-digit unique number and the password consists of six characters.  After the authentication process is done properly, the program shows a menu to the users with respect to their user role. The application meets the following requirements by these menus:

<ul>

 <li>Traders add, remove, and edit products on their shop. Each product has a unique ID, a hierarchical category, a name, a description, a price, and a discount amount.</li>

 <li>Traders see the list of orders from customers and can meet or cancel the orders.</li>

 <li>Customers can search and query the products by their names. The products that contain the search text in their name or description should be returned in the results.</li>

 <li>The search results are shown in decreasing order of the product name. Customers can sort the products in the search results by their prices, the percentage of the discount, or the name.</li>

 <li>The search results can be filtered by their category or the prices with respect to given upper or lower (or both) thresholds. The customer can filter the products not only in the lowest level category but also in any higher-level category.</li>

 <li>Customers can display all the products of a trader.</li>

</ul>

Use the following five data structures properly (do NOT use simple array structure) to implement functionalities of the application efficiently:

<ul>

 <li>ArrayList</li>

 <li>LinkedList</li>

 <li>Queue</li>

 <li>Tree</li>

 <li>Hash Table</li>

</ul>

You need to use each of them at least once, but you feel free to use more than once when you needed. Indicate which data structure is used to implement which part of the application and why you do it so in the report file. Use different sorting algorithms (your implementation) while sorting the search results by the price, the discount percentage, or the name.

There is a CSV file on the Moodle page which is named as “e-commerce-samples.csv”. Use the given csv file to create your data files. Keep the users, the orders, and the products data in your own text files. When a customer performs a search, you need to access to the products file, and return the suitable products as the result of the search. <strong>Don’t load all the products into the memory.</strong> You need to keep products in a well-organized data file for products to answer queries efficiently.