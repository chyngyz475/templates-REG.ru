# templates-REG.ru


# -*- coding: utf-8 -*-

import os, sys

sys.path.insert(0, '/var/www/u2371301/data/www/pn13.ru')

sys.path.insert(1, '/var/www/u2371301/data/djangoenv/lib/python3.8.6/site-packages')

os.environ['DJANGO_SETTINGS_MODULE'] = 'core.settings'

from django.core.wsgi import get_wsgi_application

application = get_wsgi_application()
