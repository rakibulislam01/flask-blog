# Blog using Flask

### Python secret key
```python
import secrets
secrets.token_hex(16)
'9da4faf3dbba012242abea91871a2f65'
```

>
> Sql link: [Setup SQL](https://youtu.be/cYWiDiIUxQc?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH&t=1293)
```python
# for creating database
from flaskblog import db
db.create_all()
```