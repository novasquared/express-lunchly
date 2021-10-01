1. Question: how to pull serch input from search bar?

2. Write Queries in customers.js Model:have the search input search for something unique (so probs the full name)
    a. search by first name
    b. full name
    c last name

    "last"
    split by string
    read through the array
        if one name, then search both first and last name. Return results for both

        if two names search first as first name. last as last name.

3. have the customers input array passed into customer_list.html be limited by the customers that meet the search query criteria. 