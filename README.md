# ProxyDelegate

Following the steps to complete this exercise:

1. clone this project
2. update packages: `npm ci`
3. run the test: `npm test`
4. make sure only 1 test case fails, the one that set version
5. fix the failed test case by modifying the ProxyDelegate.sol contract, e.g. add a version state variable in ProxyDelegate.sol

   - fixed it by adding the version variable as state variable in ProxyDelegate contract.

6. add a new Proxy contract which will use .call() instead of .delegatecall()
7. write test cases for the new Proxy contract to test getMsgSender() and setVersion(). Do you notice any differences between .call() and .delegatecall()?
   - change msg.sender = contract address in testcase at line 37 while testing ProxyCall contract.
8. commit your changes to github and submit your github url
