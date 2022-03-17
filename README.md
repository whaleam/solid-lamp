# solid-lamp
my workjout
f = str(1)
while f == str(1):
    print("1: ΔΔΔ     2: ΔΔY     3: ΔYΔ      4:ΔYY       5: YΔΔ      6: YΔY      7: YYΔ     8: YYY")
    g = str(input("what is your config:"))
    V = float(input("V:"))
    n1 = float(input("N1:"))
    n2 = float(input("N2:"))
    a = n2/n1
    rr = float(input("R Ω:"))
    rl = float(input("rl Ω:"))
    Zl = ((rr**2)+(rl**2))**(0.5)
    r3 = 3**(0.5)
    if g == str(1):
        print("ΔΔΔ")
        v2Φ = (V*a)
        print("V2Φ=" + str(v2Φ)+ "V")
        I2Φ = v2Φ/Zl
        
        I2 = (I2Φ)*r3
        

        I1 = I2*a
        print("I1=" + str(I1) + "A")
        print("I2="+str(I2)+ "A")
    

        
        S = I2*v2Φ*r3
        print("S="+str(S)+ "VA")
    elif g == str(2):
        print("ΔΔY")
          
        v2Φ = (V*a)

        print("V2Φ="+str(v2Φ)+ "V") 
        I2Φ = v2Φ/Zl
        I2 = I2Φ/r3
    
       
        I1 = I2*a
        print("I1="+str(I1)+"A")
        
        print("I2="+str(I2)+"A")
        
        S = I2*v2Φ*r3
        print("S="+str(S)+"VA")
    elif g == str(3):   
        print("ΔYY")
        print("V2Φ=")   
        v2Φ = (V*a)*r3
        print(v2Φ)
        I2Φ = v2Φ/Zl  
        I2 = I2Φ*r3
        print("I1=")
        I1 = I2*a*r3
        print(I1)
        print("I2=")
        print(I2)
        print("S=")
        S = I2*v2Φ*r3
        print(S)
    elif g == str(4):   
        print("ΔYΔ")
        print("V2Φ=")   
        v2Φ = (V*a)*r3
        print(v2Φ)
        I2Φ = v2Φ/Zl  
        
        I2 = I2Φ/r3
        print("I1=")
        I1 = I2*a*r3
        print(I1)
        print("I2=")
        print(I2)
        print("S=")
        S = I2*v2Φ*r3
        print(S)
    elif g == str(5):   
        print("YΔΔ")
        print("V2Φ=")   
        v2Φ = (V*a)/r3
        print(v2Φ)
        I2Φ = v2Φ/Zl  
        
        I2 = I2Φ*r3
        print("I1=")
        I1 = I2*a/r3
        print(I1)
        print("I2=")
        print(I2)
        print("S=")
        S = I2*v2Φ*r3
        print(S)
    elif g == str(6):   
        print("YΔY")
        print("V2Φ=")   
        v2Φ = (V*a)/r3
        print(v2Φ)
        I2Φ = v2Φ/Zl  
        
        I2 = I2Φ/r3
        print("I1=")
        I1 = I2*a/r3
        print(I1)
        print("I2=")
        print(I2)
        print("S=")
        S = I2*v2Φ*r3
        print(S)
    elif g == str(7):   
        print("YYΔ")
        v2Φ = (V*a)
        print(v2Φ)
        I2Φ = v2Φ/Zl
        
        I2 = (I2Φ)*r3
        
        print("I1=")
        I1 = I2*a
        print(I1)
        print("I2=")
        print(I2)

        print("S=")
        S = I2*v2Φ*r3
        print(S)
    elif g == str(8):
        print("YYY")
        print("V2Φ=")   
        v2Φ = (V*a)
        print(v2Φ)
        I2Φ = v2Φ/Zl
        I2 = I2Φ/r3
    
        print("I1=")
        I1 = I2*a
        print(I1)
        print("I2=")
        print(I2)
        print("S=")
        S = I2*v2Φ*r3
        print(S)
    else:[dev 3 pythpon.zip](https://github.com/whaleam/solid-lamp/files/8276932/dev.3.pythpon.zip)

        input("something went wron press enter to continue")
    f = str(input("1 to run again, else press enter:"))
