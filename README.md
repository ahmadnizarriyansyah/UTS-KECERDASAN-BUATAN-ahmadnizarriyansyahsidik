dates = [1982,1980,1973]
N=len(dates)

for i in range(N):
     
    print(dates[i])   
    for i in range(0,8):
    print(i)
    for year in dates:  
    print(year)  
    </div>

We can change the elements in a list:


```python
squares=['red','yellow','green','purple','blue ']

for i in range(0,5):
    print("Before square ",i, 'is',  squares[i])
    
    squares[i]='wight'
    
    print("After square ",i, 'is',  squares[i])
    
    
    squares=['red','yellow','green','purple','blue ']

for i,square in enumerate(squares):
    print(i,square)
    dates = [1982,1980,1973,2000]

i=0;
year=0
while(year!=1973):
    year=dates[i]
    i=i+1
    print(year)
    
    
print("it took ", i ,"repetitions to get out of loop")
PlayListRatings = [10,9.5,10,8,7.5,5,10,10]
</div>

<hr>

#### Write a while loop to copy the strings 'orange' of the list 'squares' to the list 'new_squares'. Stop and exit the loop if the value on the list is not 'orange':


```python
squares=['orange','orange','purple','blue ','orange']
new_squares=[];
new_squares.append(squares[i])
i=i+1
</div>

 <a href="http://cocl.us/bottemNotebooksPython101Coursera"><img src = "https://ibm.box.com/shared/static/irypdxea2q4th88zu1o1tsd06dya10go.png" width = 750, align = "center"></a>
