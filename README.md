<!DOCTYPE html>
<html>
<head>
  <title>My Python Website</title>
  <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
  <script defer src="https://pyscript.net/latest/pyscript.js"></script>
</head>
<body>
  <h1>Welcome to My Python Website</h1>

  <py-script>
    import datetime
now=datetime.datetime.today()
year,month,day=map(int,input("enter birth year month and day:").split())
birth_day=datetime.datetime(year,month,day)
survived=now-birth_day
print(f"you survived survived :{survived.days} days")
  </py-script>
</body>
</html>
