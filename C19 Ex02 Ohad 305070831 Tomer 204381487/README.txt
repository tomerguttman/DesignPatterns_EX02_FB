==========Ex02 Checking Report==========
Exercise No...........: 01
First Student Details.: 305070831 - Ohad Slutzky
Second Student Details: 204381487 - Tomer Guttman
Delivery Date.........: 10 - Aug - 2019
Delivered In Delay....: No
Delay Reason..........: 
Visual Studio Version.: 2015
Comments..............: 1.In the first tab of the application, when selecting a date in the calendar, an error message appears beacause
						  we are attempting to access the birth date of a the user's friends. That field is not accessible therefore an
						  exception is thrown.
						
						2.The lines 98 and 311 in the code are in comment because when attempting to access the hometown field of the 
						user and his friends, an exception is thrown because those fields are not accesible. When initializing the 
						application form, we are trying to use said fields and in the process we catch an exception that prevents us
						from completing the initialization process. That is why said lines are in comment because otherwise the 
						application fails to run.

						3.Some of the methods in the code are those who are automatically generated by the FacebookForm changes,clickes etc... 
						  we didn't change their names and parameters names according to the format because we were said not to "touch" them.

==========End Ex02 Checking Report==========