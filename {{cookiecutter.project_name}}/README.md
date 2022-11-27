# {{cookiecutter.project_title}}

{{cookiecutter.project_description}}

## Install and run

### Development

#### Install
```bash
git clone {{cookiecutter.project_repo}} {{cookiecutter.project_name}}
```
```bash
cd {{cookiecutter.project_name}}
```
```bash
pip install -e .
```

#### Config
```bash
cat > .env << DOTENV
DOTENV
```

#### Prepare
```bash
```

#### Run
```bash
python -m {{cookiecutter.python_namespace}}.{{cookiecutter.project_slug}}
```

### Production

#### Install
Replace `$VERSION` with the desired version number, e.g. `1.0.0`.
```bash
pip install {{cookiecutter.project_name}}@git+{{cookiecutter.project_repo}}@$VERSION
```

#### Config
```bash
```

#### Prepare
```bash
```

#### Run
```bash
python -m {{cookiecutter.python_namespace}}.{{cookiecutter.project_slug}}
```

# Environment variables

| Name | Default value | Description |
|------|---------------|-------------|
|      |               |             |
