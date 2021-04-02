## Welcome!!!
### AddCalc (Address Calculator)
#### Introduction:
```
This is the Calculator to calculate the address of the element with in an Array at a particular index.

There are mainly two ways to store an element in an Array and represent them which are mention below:
```
##### Row Major Representation:
```
Row Major Representation is a method of representing multi dimension array in sequential memory.
In row-major representation, the elements of Matrix  are stored row-wise,
i.e., elements of 1st row, 2nd row, 3rd  row, and so on till mth row.
```

##### Column Major Representation:
```
Column Major Representation is a method of representing multi dimension array in sequential memory.
In column-major representation, the elements of Matrix  are stored column-wise,
i.e., elements of 1st column, 2nd column, 3rd  column and so on till mth column
```
##### Code:
```python
 
def oneD(B,D):   
	LB=int(input("enter Lower Bound : "))
	index=int(input("Enter index :"))
	a=B+(D*(I-LB))
	print("1D -> ",a) 


def twoDR(B,D):
	r=int(input("Enter no. of Rows: "))
	c=int(input("Enter no. of Column: "))
	i=int(input("Enter i : "))
	a
	j=int(input("Enter j : "))
	b=B+D*((i*c)+j)
	print("2D Row -> ",b)
	c=B+D*((j*r)+i)
	print("2D column -> ",c)

def twoDB(B,D):
	lr=int(input("Enter lower bound of Row: "))
	ur=int(input("Enter upper bound of Row: "))
	lc=int(input("Ente lower bound of Column: "))
	uc=int(input("Ente upper bound of Column: "))
	I=int(input("Enter i : "))
	J=int(input("Enter j : "))
	r=(ur-lr)+1
	c=(uc-lc)+1
	i=I-lr
	j=J-lc
	print(r)
	print(c)
	print(i)
	print(j)


	d=B+D*(((i)*c)+(j))
	e=B+D*(((j)*r)+(i))

	print("2D Row -> ",d)
	print("2D column -> ",e)	





base=int(input("Enter Base Address :"))
data=int(input("data size :"))




print("Adress Calculator")
print("1-> 1D Array Address")
print("2-> 2D Array Adress ")
print("3-> 2D Array with bounds")

choice=int(input("Enter the choice: "))
if choice==1:
	oneD(base,data)
elif  choice==2:
	twoDR(base, data)
else:
	twoDB(base, data)
```




