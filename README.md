# Snake Game

---

## Dev Setup

Load Python 3.13.0 in `~/.pyenv/versions/3.13.0` (just one time)

```bash
pyenv install 3.13.0
```

Create virtual environment `snake-env` in `~/.pyenv/versions` with Python 3.13.0 (just one time)

```bash
pyenv virtualenv 3.13.0 snake-env
```

Navigate to project (everytime)

```bash
cd ~/projects/snake
```

Start projekt with virtual env `snake-env` (just one time)

```bash
pyenv local snake-env
```

Install dependencies (just one time)

```bash
pip install -r requirements.txt
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

---

## Docker
