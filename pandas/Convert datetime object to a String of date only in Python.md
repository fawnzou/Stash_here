(https://stackoverflow.com/questions/10624937/convert-datetime-object-to-a-string-of-date-only-in-python)

import datetime
t = datetime.datetime(2012, 2, 23, 0, 0)
t.strftime('%m/%d/%Y')

will yield:
'02/23/2012'
