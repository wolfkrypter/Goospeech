# Goospeech
Este shell script transcodifica texto a audio almacenable en formato de audio mp3 con <a href="https://gtts.readthedocs.io/en/latest">gTTS</a> y una conexión a una red de internet. 

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
<a href="https://freeimage.host/i/3pvyIa4"><img src="https://iili.io/3pvyIa4.md.png" alt="Goospeech" border="0"></a>



<h2>Desinstalación de Goospeech</h2>

```bash
urlruta=$(pwd) && cd $PATH && rm -r goospeech && cd $urlruta && unset -v urlruta
```


```bash
yes | rm -r Goospeech
```



