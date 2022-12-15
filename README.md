# tool1
tool
import re
pattern = re.compile(ur'\w[-\w.+]*@([A-Za-z0-9][-A-Za-z0-9]+\.)+[A-Za-z]{2,14}')
str = u''
print(pattern.search(str))
