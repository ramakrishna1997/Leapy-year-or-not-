# Leapy-year-or-not-
Write a program given year is leap or not 




var year=1995;
if(year%4===0){
    if(year%100==0){
        if(year%400==0){
        }else{
            console.log("The given year" + year + " is a leap year");
        }
    }else{
        console.log("The given year" + year+ " is a leap year");
    }
}else{
    console.log("The given year" + year + " not a leap year");
}
