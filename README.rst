=====
django_exportapp
=====

django_exportapp is a simple Django app to export models xml fixtures.

Quick start
-----------

1. Add "django-exportapp" to your INSTALLED_APPS setting like this::

        INSTALLED_APPS = (
          ...
          'django_exportapp',
        )

2. Add add variables to settings project like this::

        EXPORTAPP_PREFIX_NAME = 'myproject'
        EXPORTAPP_PUBLIC_DIR = '/home/user/dpub'
        EXPORTAPP_PRIVATE_DIR = '/home/user/private'
        EXPORTAPP_ARCH_DIR = '/home/user/arch'
