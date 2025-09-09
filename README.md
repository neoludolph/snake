# Snake Game

---

## Dev Setup (you need Linux or MacOS for development)

### First time commands

If pyenv is not installed (Linux)

```bash
curl -fsSL https://pyenv.run | bash
```

If pyenv-virtualenv is not installed (first step is recommended for WSL Users)

```bash
git config --global core.autocrlf input
```

```bash
git clone https://github.com/pyenv/pyenv-virtualenv.git $(pyenv root)/plugins/pyenv-virtualenv
```

```bash
echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.bashrc
```

```bash
exec "$SHELL"
```

MacOS (pyenv)

```bash
brew update
brew install pyenv
```

pyenv-virtualenv

```bash
brew install pyenv-virtualenv
```

Do this just once

```bash
eval "$(pyenv virtualenv-init -)"
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
