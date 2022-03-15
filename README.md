Execution:
1. Please download the zip and open the visual studio solution.
2. Create two windows environment variables under system variables with the names "AccessKey" to store the AWS access key retrieved from Saltify, "SecretKey" to store the AWS secret key retrieved from Saltify. Restart the windows machine after the creation of keys.
3. Open the solution, right click the solution and click build/rebuild solution (the build order of projects is defined)
4. To get to the executable console application, navigate to $/Prokeep/Prokeep.Exercise/bin/Debug or Release and double click Prokeep.Exercise.exe
5. The contacts JSON should be pretty printed on to the console screen
6. Close the console to close the app.
7. If there are any errors during execution, that error will be displayed on the console

Unit Test:
1. To unit test the application to assert the output is a valid JSON, open solution in visual studio build/rebuild the solution
2. In VS, click on TEST->Run->All Tests
3. If the unit test passed, a green check will be displayed in VS
4. If the unit test failed, a red cross will be displayed in VS
