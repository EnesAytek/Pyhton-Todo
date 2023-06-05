# Django ORM Query

'''
shell
python manage.py shell
'''

'''
python
# Todo Modelini İmport Etmek
from todo.models import Todo

# Tüm Objeler
Todo.objects.all()

# Tüm Objeleri Say
Todo.objects.all().count()

# Yeni Todo Oluşturmak
Todo.objects.create(title="Yeni Başlık İsmi")
Todo.objects.create(title="Yeni Başlık İsmi" is_active=True)

# is_active Olanları Göster
Todo.objects.filter(is_active=True)

# is_active Olanları Say
Todo.objects.filter(is_active=True).count()

# UPDATE
# Yapılan sorguya uyan objelerin istenilen alanları değiştirilebilir
Todo.objects.filter(is_active=False).update(is_active=True)

'''