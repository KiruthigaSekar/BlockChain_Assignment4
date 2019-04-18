# BlockChain_Assignment4

Name : Kiruthiga Sekar

I have used **RemixIDE** https://remix.ethereum.org/#optimize=false&version=soljson-v0.5.1+commit.c8a2cb62.js, to create and test, test functions.
Compatible with **solidity 0.5 or higher**

_*Appropriate Screenshots are provided*_ 

Created a Course.sol file, based on the tutorial and is compatible with solidity 0.5 and higher.

In the link specified above,Local file can be selected by simply clicking on the open folder icon on the top left corner.


Following are the steps to *compile, run and test* the contract:

1. Once the .sol file is opened, select the compiler from the **Select new compiler version** dropdown list, under the *Compile* tab. I have selected the following compiler 

*Current version:0.5.0+commit.1d4f565a.Emscripten.clang*

2. Now we can run the contract, by selecting **JavaScript VM** under the *Run* tab. Default address will be displayed once the JavaScript VM is selected, there is a *Copy value to Clipboard* option next to the address, we copy the address for future reference. Let the Gas Limit and Value be un changed.

3. Click on **Deploy**, to deploy our contract. Once it is done, the deployed contracts can be viewed under **Deployed Contracts**, click on it to view the functions of the contract.

4. The following are the functions of the contract:

i. **setInstructor** => used to create a new instructor, it takes *address(which we have copied earlier), integer for age, string for fName and lName* as parameters. Example input that I provided: 
    "0xca35b7d915458ef540ade6068dfe2f44e8fa733c",20,"Kirthi","Sekar"  
    **Address,fName and lName has to be enclosed within double quotes**
click on *setInstructor* button to add an intructor
    
ii. **getInstructor** => used to return the age, fName and lName of the instructor. Paste the address that we've copied earlier. Example input that I provided:
    "0xca35b7d915458ef540ade6068dfe2f44e8fa733c"  
    **Address has to be enclosed within double quotes**
click on *getInstructor* button. Obtained Output:
    0: uint256: 20
    1: string: Kirthi
    2: string: Sekar
    
iii. **getInstructors** => used to return the address of the instructor. Click on *getInstructor* button after pasting the address. Example output:
    0: address[]: 0xCA35b7d915458EF540aDe6068dFe2F44E8fa733c,0xCA35b7d915458EF540aDe6068dFe2F44E8fa733c
    *I've added the same entry twice by mistake*
    
iv. **countInstructor** => used to return the number of instructor. Click on the *countInstructor* button. Example Output:
    0: uint256: 2 *Note: Same entry made twice*
   
***Following the above procedure many records can be created and the working of the function can be tested*
