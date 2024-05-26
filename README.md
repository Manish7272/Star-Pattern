# Star-Pattern

<br>

# 1

![Screenshot 2024-05-26 155641](https://github.com/Manish7272/Star-Pattern/assets/71213166/0930fea7-9ef1-4fde-80a7-1cd36ee98bba)

    for i in range(1,5):
        for j in range(1,5):
            if j<=i:
                print("*", end=" ")
            else:
                print(" ", end=" ")
        print(" ")


<br>

# 2

![Screenshot 2024-05-26 161810](https://github.com/Manish7272/Star-Pattern/assets/71213166/7c5423f4-1d4c-48f4-b133-21386e2df5e4)

    for i in range(1,5):
        for j in range(1,5):
            if j>=i:
                print("*", end=" ")
            
        print(" ")


<br>

# 3

![Screenshot 2024-05-26 155736](https://github.com/Manish7272/Star-Pattern/assets/71213166/4b6ae21a-3c70-48b6-ba64-30409345dc17)

    for i in range(1,5):
        for j in range(1,5):
            if j<=5-i:
                print("*", end=" ")
            else:
                print(" ", end=" ")
        print()

<br>

# 4

![Screenshot 2024-05-26 161719](https://github.com/Manish7272/Star-Pattern/assets/71213166/dc5b2d8c-a511-4267-a3e5-09098b560d60)

    for i in range(1,5):
        for j in range(1,5):
            if j>=5-i:
                print("*", end=" ")
            else:
                print(" ", end=" ")
        print()


<br>
<br>

<br>

# 5

![Screenshot 2024-05-26 161847](https://github.com/Manish7272/Star-Pattern/assets/71213166/0a4c3e9e-583d-41d3-843c-b75daefeb641)

    for i in range(1,5):
        for j in range(1,8):
            if j>=5-i and j<=3+i:
                print("*", end=" ")
            else:
                print(" ",end=" " )
        print()

<br>

# 6

![Screenshot 2024-05-26 161925](https://github.com/Manish7272/Star-Pattern/assets/71213166/d23e823c-9317-4400-9048-3b3a7f4ee6a1)

    for i in range(1,5):
        for j in range(1,8):
            if j>=i and j<=8-i:
                print("*", end=" ")
            else:
                print(" ",end=" " )
        print()

<br>

# 7
![Screenshot 2024-05-26 162013](https://github.com/Manish7272/Star-Pattern/assets/71213166/8c5a71e0-9e53-4670-a59e-40635046c67b)

    for i in range(1,5):
        for j in range(1,8):
            if j<=5-i or j>=3+i:
                print("*", end=" ")
            else:
                print(" ", end=" ")
        print("")

<hr>

# 8 
![Screenshot 2024-05-26 162042](https://github.com/Manish7272/Star-Pattern/assets/71213166/9ad9abf2-ab74-4608-9656-f41b7906dbaa)

    for i in range(1,5):
        for j in range(1,5):
            if j<=i:
                print(j, end=" ")
            else:
                print(" ", end=" ")
        print()
        

<br>

# 9

![Screenshot 2024-05-26 173726](https://github.com/Manish7272/Star-Pattern/assets/71213166/073d2e0c-d888-4829-8b82-2ecfd676d4af)

    for i in range(1,6):
        k=6-i
        for j in range(1,6):
            if j<=6-i:
                print(k, end=" ")
                k=k-1
            else:
                print(" ", end=" ")
        print()
        























