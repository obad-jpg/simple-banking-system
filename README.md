# vowel/consonants

string = input().lower()
vowels = 'aeiou'
for i in string:
	if i.isalpha() is False:
		break
	if i.isalpha():
		if i in vowels:
			print('vowel')
		else:
			print('consonant')
