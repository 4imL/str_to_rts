# str_to_rts
문자열을 거꾸로 출력
str = input("원본 문자열 ==>")
rts = ""
i = len(str)

while i > 0 :
	rts += str[i - 1]
	i -= 1

print("반대 문자열 ==> ", rts)
