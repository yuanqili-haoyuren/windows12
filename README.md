# How to Setup your Windows Machine

- Windows Terminal
- Shell
- Windows Subsystem for Linux (Ubuntu)


## Git and GibHub

```
git config -–global user.name "your_username"
git config --global user.email "your_email@example.com"
```

Change the following line

```
git remote add origin https://github.com/<username>/<project-name>.git
```

to 

```
git remote add origin git@github.com:<username>/<project-name>.git
```

[Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

```
ssh-keygen -t ed25519 -C "your_email@example.com"
ssh-add ~/.ssh/id_ed25519
```

### Public and Private key

- $(\text{public key}, \text{private key})$
- $\text{private}(\text{public}(\text{plaintext})) = \text{plaintext}$
- $\text{public}(\text{private}(\text{plaintext})) = \text{plaintext}$

## Common Git Commands

```
git add ...
git commit -m "..."
git push
```

