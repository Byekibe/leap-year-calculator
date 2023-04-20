# I'll keep this repo. Why? I was learning Python and I struggled using github I was new and wondering what is this, I love to keep memories. I'll make no changes, I just realized as I was going through my repos and deleting what's not important that I did not commit any code!! Haha 😂😂😂  that was me 2 or 3 years 😍😍, I love myself. I am nostalgic and my eyes feel wet, Should I cry since I pity me 2 or 3 years ago? 

# leap-year-calculator
year = int(input("Please ENTER the year: "))

if year%4 == 0:
    if year%100 == 0:
        if year%400 == 0:
            print(f"{year} is a leap year")
            
        else:
            print(f"{year} is not a leap year")
    else:
        print(f"{year} is a leap year")
else:
    print(f"{year} is not a leap year")
    
