как создать ssh ключ
Open Terminal.

Paste the text below, substituting in your GitHub email address.

ssh-keygen -t ed25519 -C "your_email@example.com"
Note: If you are using a legacy system that doesn't support the Ed25519 algorithm, use:

 ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
This creates a new SSH key, using the provided email as a label.

> Generating public/private ALGORITHM key pair.
When you're prompted to "Enter a file in which to save the key", you can press Enter to accept the default file location. Please note that if you created SSH keys previously, ssh-keygen may ask you to rewrite another key, in which case we recommend creating a custom-named SSH key. To do so, type the default file location and replace id_ssh_keyname with your custom key name.

> Enter a file in which to save the key (/home/YOU/.ssh/ALGORITHM):[Press enter]
At the prompt, type a secure passphrase. For more information, see "Working with SSH key passphrases."

> Enter passphrase (empty for no passphrase): [Type a passphrase]
> Enter same passphrase again: [Type passphrase again]

чтобы добавить ключ на аккаунте гит хаб нужнт зайти в настройким

чтобы склонировать репозиторий
ввести команду git clone git@github.com:Dimabobrovskiy/repository.git



