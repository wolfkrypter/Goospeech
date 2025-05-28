# Goospeech
Shell script transcodificador de texto a audio con gTTS

<h1>Instalación de Goospeech</h1>

```bash
yes | termux-setup-storage
```

```bash
yes | pkg install python
```

```bash
yes | pkg install git
```


```bash
pip install gtts
```

```bash
git clone https://github.com/wolfkrypter/Goospeech.git
```

```bash
cd Goospeech && chmod +x goospeech && mv goospeech $PATH
```




<h2>Ejecución de Goospeech</h2>

```bash
goospeech
```




<h2>Desinstalación de Goospeech</h2>

```bash
urlruta=$(pwd) && cd $PATH && rm -r goospeech && cd $urlip && unset -v urlruta
```


```bash
yes | rm -r Goospeech
```



