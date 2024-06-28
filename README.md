# Sandbox for JAX based design space exploration for health monitoring data

## Setup
- Install: `pip install -r requirements.txt`
- CPU only -> less machine specific

### Freeze reqs with upward compat
- `pip freeze |sed s/==/\>=/ > requirements.txt`

### Un/-track sandbox notebook
- `git update-index --assume-unchanged <file>`
- `git update-index --no-assume-unchanged <file>`
