# ToDo-Task
It is a simple and  basic ToDo List application By using Kotlin. 

It Deals with the Basic Functionality Like:


	* Creating a task.
	* We can Edit that task.
	* We can Delete that task.
	* We can Mark as complete. 
	* We can Reset the task.
	* We can create a Sub-task.
	* For a single Task u can have N no of subtask.
	* once The Sub-task is over u can mark it as complete manually.
	* U can Update or Edit the sub-task.
	* u can Delete the Sub-task.
By Dealing with this app u can familier with some of the concept of Kotlin Like:
	-> RecyclerView:
		A RecyclerView is essentially a ViewGroup of containers called ViewHolders which populate a particular item.
		 RecyclerView is an extensive and exhaustive Android class to provide a flexible UI.
		 A huge benefit of using RecyclerView is that you’re able to is efficiently reuse views 
		instead of managing items that aren’t even visible to a user. 
		You can think of those containers as a way to recycle the population of those view instances.

* IN THESE APPLICATION RECYCLERVIEW IS USED FOR DISPLAYING THE TASK.
	

	-> SQLite Database:
		SQLite is an open-source relational database that is used to perform database operations on Android devices such as storing,
		 manipulating or retrieving persistent data from the database.



* IN THESE APPLICATION SQLITE DATABASE IS USED FOR STORING AND RETRIVIENG THE TASK AND SUB-TASK .

	->lateinit:
		lateinit means late initialization. 
		If you do not want to initialize a variable in the constructor instead you want to initialize it later
		on and if you can guarantee the initialization before using it, then declare that variable with lateinit keyword. 
		It will not allocate memory until initialized.



* IN THESE APPLICATION lateinit IS USED TO CALL THE DATABASE HANDLER CLASS IN THE .ACTIVITY CLASS WHERE IT IS USED


	->Higher-Order Functions and Lambdas:
			Kotlin functions are first-class, which means that they can be stored in variables and data structures, 
			passed as arguments to and returned from other higher-order functions. 
			You can operate with functions in any way that is possible for other non-function values
		
* IN THESE APPLICATION Higher-Order Functions and Lambdas ARE USED IN FUNCTION LIKE TO CREATE,EDIT,DELETE,UPDATE A TASK
*AND SOME OTHER BASIC CONCEPTS LIKE data types, operators, variables AND ETC....



 
