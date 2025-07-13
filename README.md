🔹 Python Strings 

🔸 Basics
- A string is a sequence of characters inside ' ', " ", or triple quotes.
  - Example: s = "Hello World"

🔸 Indexing & Slicing
- Indexing starts at 0; negative indexes count from end.
  - s[0] → 'H', s[-1] → 'd'
- Slicing: s[start:stop:step]
  - s[0:5] → 'Hello'
  - s[::-1] → reversed string

🔸 String Operations
- Concatenation: 'Hello' + 'World'
- Repetition: 'Hi' * 3 → 'HiHiHi'
- Membership: 'H' in s → True

🔸 String Methods
- Case: .lower(), .upper(), .capitalize(), .title()
- Trim: .strip(), .lstrip(), .rstrip()
- Replace: .replace('old', 'new')
- Find: .find('sub'), .index('sub')
- Split/Join: .split(','), ' '.join(list)
- Check: .startswith('H'), .endswith('d')
- Character checks: .isalpha(), .isdigit(), .isalnum(), .isspace()

🔸 Formatting Strings
- f-string: f"Hello {name}"
- .format(): "Hello {}".format(name)

🔸 Useful Functions
- len(s) → length of string
- ord('A') → ASCII code (65)
- chr(65) → Character ('A')
- sorted(s) → List of sorted characters

🔸 Immutability
- Strings cannot be changed in-place.

🔸 Loops
for ch in s:
    print(ch)

🔸 Examples
- Reverse: s[::-1]
- Palindrome: s == s[::-1]
- Count letter: s.count('a')

🔸Followings are the two Projects on Strings
1.Password Strength Checker
2.Palindrome Checker
