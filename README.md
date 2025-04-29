# Salva_exercici
# 📰 Aplicació Flask per a llegir RSS de diaris

Aquest projecte és una aplicació en **Flask** que permet llegir notícies a partir de **fonts RSS** de **La Vanguardia**. Els usuaris poden accedir a les notícies en mode **remot** o **local**.

---

### Entorns Virtuals
Informació sobre venv

####Per començar a treballar amb un entorn virtual, el primer pas és crear-lo. Per això, obre un terminal integrat des del Visual Code i executa:

**Amb linux:**

`python3 -m venv .venv´

**Amb windows:**

`python -m venv .venv´

####El següent pas és activar-lo. Per això executa:

**Amb linux:**

`source .venv/bin/activate´

**Amb Windows:**

.venv\Scripts\activate

Al prompt veuràs que ets dins de l'entorn

####Ara ja pots instal·lar els paquets que necessitis, com són:

pip install flask
pip install feedparser

####Per sortir de l'entorn virtual, executa:

deactivate

###Finalment, per a Visual Code l'extensió Python Environment Manager facilita la integració entre el Visual Code i l'entorn virtual.
Flask
####Per inicial l'aplicació cal executar des del terminal integrat del Visual Code:

flask run --debug

Desprès, obrir un navegador a l'adreça **http://127.0.0.1:5000/**

Per aturar el servidor flask, fes **CTRL + C** al terminal integrat.

