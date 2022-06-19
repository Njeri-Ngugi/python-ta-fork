#_init_.py
#app.py
def solution(n):
   def solution(n):
    x = 1
    for x in n:
        if n % x == 0:
            x = x + 1
    if n == 2:
        print("The number is a prime number")
    else:
        print("The number is not a prime number")

if __name__ == "__main__":
    if len(sys.argv) <= 1:
        sys.exit(os.error("Argument required"))

    n = int(sys.argv[1])
    print(solution(n))
