# secret-gen

A Python script to generate random, cryptographically secure passwords and PIN codes

## Download

Open a terminal emulator and clone the repository:
```bash
git clone https://github.com/xxyrnn/secret-gen.git
```

Change folder to the newly cloned repository:
```bash
cd secret-gen
```

Finally run the script:
```bash
python main.py <PASS|PIN> <length> # Windows
python3 main.py <PASS|PIN> <length> # Linux/MacOS
```

## Example usage

```bash
python3 main.py PASS 20 # generates a 20 characters long password
python3 main.py PIN 6 # generates a 6 digits long PIN code
```
