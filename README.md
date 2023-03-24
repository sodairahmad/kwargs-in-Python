# kwargs-in-Python

def show(*args, **kwargs):
    print(type(args))
    print(type(kwargs))
    for arg in args:
        print(arg,end=" ")
    print()
    for key,value in kwargs.items():
        print(key,value)


show("Sodair", "Ahmad", "Engineer", dep="Mining", sec= "A", sescission = "2020")

