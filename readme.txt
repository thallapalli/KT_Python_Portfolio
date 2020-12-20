#step 1
python3 -m venv pathtoyourworking directory (<C> /KT_Portfolio_Python )
@step2
in cmd got o C:\Users\13033\git\KT_Python_Portfolio
 then issue Scripts\activate  (note \ here)
step4
(KT_Portfolio_Python) C:\Users\13033\eclipse-workspace2\KT_Portfolio_Python> pip install Flask
step5
set FLASK_APP=server.py
step6
set FLAST_ENV=development
step7
flask run

Deploy steps
pip freeze > requirements.txt

goto python anywhere
create your own account

import sys
path = '/home/karnakar/KT_Python_Portfolio'
if path not in sys.path:
    sys.path.append(path)

from server import app as application



