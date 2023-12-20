```
main() {
    self welcomePrinter = new self("Welcome to Crash - The Programming Language!");
    
    welcomePrinter.printWelcome();
}

class {
    String welcome;
    
    public (String welcome) {
        this.welcome = welcome;
    }    
    
    public printWelcome() {
        info(this.welcome);
    }
}
```
