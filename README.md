# Django Blueprint

[![PyPI version](https://badge.fury.io/py/django-blueprint.svg)](https://badge.fury.io/py/django-blueprint)
[![Python versions](https://img.shields.io/pypi/pyversions/django-blueprint.svg)](https://pypi.org/project/django-blueprint/)
[![Django versions](https://img.shields.io/badge/django-5.0%2B-blue.svg)](https://www.djangoproject.com/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

With Django Blueprint you can easily create your own CMS.


## 🚀 Quick Start

### Installation

☝️ Django Blueprint depends on Django.

```bash
pip install django-blueprint
```

### Add to Django Settings

```python
# settings.py
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'blueprint',  # Add this
    # ... your apps
]
```

## 🛠️ Requirements

- Python 3.12+
- Django 5.0+

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Add tests for your changes
5. Run the test suite (`python manage.py test`)
6. Commit your changes (`git commit -m 'Add amazing feature'`)
7. Push to the branch (`git push origin feature/amazing-feature`)
8. Open a Pull Request

### Development Setup

```bash
# Clone the repository
git clone https://github.com/BitsOfAbstraction/django-blueprint.git
cd django-blueprint

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
poetry install
```

## 📚 Documentation

For detailed documentation, visit [djangoheadless.org](https://djangoheadless.org)

## 🐛 Issues & Support

- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/BitsOfAbstraction/django-blueprint/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/BitsOfAbstraction/django-blueprint/discussions)
- 📧 **Email**: leon@devtastic.io

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built on the shoulders of [Django](https://www.djangoproject.com/)
- Inspired by the headless CMS and Jamstack movement
- Thanks to all contributors and the Django community

## 🔗 Links

- [PyPI Package](https://pypi.org/project/django-blueprint/)
- [Documentation](https:/djangoheadless.org)
- [GitHub Repository](https://github.com/BitsOfAbstraction/django-blueprint)
- [Changelog](CHANGELOG.md)

---

Made in Europe 🇪🇺 with 💚 for Django