# LoanBankingUsingErlang

Multiple customers threads interacts with multiple bank to satisfy their loan needs. Uses threads to achieve concurrency and parallelism.

### Prerequisites and Running

What things you need to install the software and how to install them

```
1. Operating System : Windows 10
2. Erlang 10.4 or higher
3. Java 1.8 or higher
4. customers.txt and banks.txt 
5.Erlang commands: 
Run command in erlang shell as follows(keep txt files where project is kept):
    cd("path of folder").
    c(money).
    money:start().
Erlang commands: 
Run command in cmd as follows(keep txt files where project is kept):
    javac Bank.java
    javac Customer.java
    javac Money.java
    java Money
```

### Technical Details

```
Erlang 10.4
Java 1.8
```

### Test Cases

It will print customer requests for loan and bank responses correspondingly and also prints the total loan availed and funds remaining at the banks.

### More Information

Refer A3.pdf for assignment details
