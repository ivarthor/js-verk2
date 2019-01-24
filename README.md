1) let eg = {
        nafn: "ívar",
        kennitala: "0901013310",
        heimilisfang: "Skólabraut,
        heimasimi: "422-5775",
        gsm: "618-4034"        
};

2) for (let x in eg) {
       console.log(key);
       console.log(eg[key]);
};

3) let eg = {
        nafn: "ívar",
        kennitala: "0901013310",
        heimilisfang: "Skólabraut,
        heimasimi: "422-5775",
        gsm: "618-4034"
        fun: function() {return "ívar 18"}
};

4) console.log(family.parents.fathers[1])

5) let breakfast = {
    name: "The Lumberjack",
    price: "$9.95",
    ingredients: ["eggs","sausage","toast","hashbrowns","pancakes"]
};

6) var savingsAccount = {
    balance: 1000,
    interestRatePercent: 1,
    deposit: function addMoney(amount) {
        if (amount > 0) {
            savingsAccount.balance += amount;
        }
    },
    withdraw: function removeMoney(amount) {
        var verifyBalance = savingsAccount.balance - amount;
        if (amount > 0 && verifyBalance >= 0) {
            savingsAccount.balance -= amount;
        }
    },
    printAccountSummary: function() {
        
        return "Welcome!" + "\n" + "Your balance is currently" + " " + "$" + savingsAccount.balance + " " + "and your interest rate is" + " " + savingsAccount.interestRatePercent + "%.";
    }
};

console.log(savingsAccount.printAccountSummary());

7) var donuts = [
    { type: "Jelly", cost: 1.22 },
    { type: "Chocolate", cost: 2.45 },
    { type: "Cider", cost: 1.59 },
    { type: "Boston Cream", cost: 5.99 }
];

donuts.forEach(function(i){
   console.log(i.type + " " + "donuts cost $" + i.cost + " " + "each"); 
});

8) Þau eru óröðuð. Þegar það er sett hluti inní objectið þá er ekki gefið röð.

9) það er búið til object og síðan er búið til breytu sem bendir til objectið.

10) því age er bætt við objectið þegar það er gert user.age = 25
