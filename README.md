# Snake Game

---

## Dev Setup (you need Linux or MacOS for development)

### First time commands

If not installed

```bash
curl -fsSL https://pyenv.run | bash
```

Load Python 3.13.0 in `~/.pyenv/versions/3.13.0`

```bash
pyenv install 3.13.0
```

Create virtual environment `snake-env` in `~/.pyenv/versions` with Python 3.13.0

```bash
pyenv virtualenv 3.13.0 snake-env
```

Navigate to project

```bash
cd ~/projects/snake
```

Start projekt with virtual env `snake-env`

```bash
pyenv local snake-env
```

Install dependencies

```bash
pip install -r requirements.txt
```

### Everytime command

```bash
cd ~/projects/snake
```

### Wanna change Python version?

```bash
pyenv install <new version>
```

```bash
pyenv virtualenv <new version> <new virtualenv>
```

```bash
cd ~/projects/snake
```

```bash
pyenv local <new virtualenv>
```

```bash
pip install -r requirements.txt
```

---

## Docker
