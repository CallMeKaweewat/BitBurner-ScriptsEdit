
Display a .msg, .lit, or .txt file
  
**Signature:**

  
```typescript

cat [file]

```

  

## Parameters

  
- `cat`: command followed by the name of a file, it will output the entire content of that file to the terminal.


**Example:**


  
```typescript

cat hackers-starting-handbook.lit

```

  

**Result:**
This example word in hackers-starting-handbook.lit file

```Terminal
  
_The Beginner's Guide to Hacking_  
  
When starting out, hacking is the most profitable way to earn money and progress. This is a brief collection of tips/pointers on how to make the most out of your hacking scripts.  
  
-hack() and grow() both work by percentages. hack() steals a certain percentage of the money on a server, and grow() increases the amount of money on a server by some percentage (multiplicatively)  
  
-Because hack() and grow() work by percentages, they are more effective if the target server has a high amount of money. Therefore, you should try to increase the amount of money on a server (using grow()) to a certain amount before hacking it. Two important Netscript functions for this are getServerMoneyAvailable() and getServerMaxMoney()  
  
-Keep security level low. Security level affects everything when hacking. Two important Netscript functions for this are getServerSecurityLevel() and getServerMinSecurityLevel()  
  
-Purchase additional servers by visiting 'Alpha Enterprises' in the city. They are relatively cheap and give you valuable RAM to run more scripts early in the game  
  
-Prioritize upgrading the RAM on your home computer. This can also be done at 'Alpha Enterprises'  
  
-Many low level servers have free RAM. You can use this RAM to run your scripts. Use the scp Terminal or Netscript command to copy your scripts onto these servers and then run them.

```

