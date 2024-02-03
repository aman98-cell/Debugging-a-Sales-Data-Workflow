Sometimes, things that once worked perfectly suddenly hit a snag. This sales workflow is no exception. The `load_and_check()` function worked great until the last update. Now, along with new data, there seem to be some issues. You've been asked to check it out!

The `load_and_check()` function loads the `sales.csv` dataset and proceeds to do some checks. First, it confirms that the dataset has the desired shape. Next, there are a couple of integrity checks designed to make sure that the data is consistent and that nothing suspicious is happening there. 

The `sales.csv` dataset contains several columns, but you should give special attention to these:
`Total`: The total price, including 5% tax
`Quantity`: Number of products purchased
`Unit price`: Price of each product in USD
`Tax`: 5% tax fee, calculated from the total price
`Date`: Date of the purchase

As you work on fixing the pipeline, try to keep as much of the original code as possible. If you need to change something in the data, create new columns and keep all original ones intact. Remember to update the `if` statements of checks if necessary!
