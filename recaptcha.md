# Alternative etiche a Google reCAPTCHA

Molti siti web oggigiorno usano il servizio reCAPTCHA di Google per provare a verificare che 
i visitatori siano persone reali. Mentre ciò è utile per prevenire l'abuso dei siti da parte 
dei bot, aiuta anche Google a [violare la privacy delle persone](https://www.fastcompany.com/90369697/googles-new-recaptcha-has-a-dark-side). 

Inoltre, a causa della loro natura deliberatamente inaccessibile, reCAPTCHA e similari 
causano seri problemi di accessibilità per coloro con ipovisione o ipoacusia. 
L'indovinello visuale è invisibile a persone che usano browser web non visuali (come i lettori 
di schermo), e la sfida auditiva può essere abbastanza difficile da superare. 

Se gestisci un sito web e tieni a cuore la sua privacy ed accessibilità, potresti voler 
considerare delle alternative a reCAPTCHA. 

## Ti serve davvero reCAPTCHA?

C'è un [ottimo saggio](https://kevv.net/you-probably-dont-need-recaptcha/) che esplora 
minuziosamente l'argomento Google reCAPTCHA, le captcha in generale e se il tuo sito ne 
ha bisogno. 

È fortemente raccomandato che i gestori di siti web vi diano una lettura prima di decidere 
quale opzione è giusta per loro. 

**SITO WEB** - [You (probably) don't need ReCAPTCHA](https://kevv.net/you-probably-dont-need-recaptcha/)

## Honeypot

Invece di chiedere agli umani di identificarsi, si può provare a fregare i bot in modo che si 
rivelino, interagendo con degli "honeypot". 

Gli honeypot sono elementi di una pagina web che sono invisibili ai veri umani, ma visibili 
ai bot. Se si registra interazione con questi ultimi, potrebbe essere abbastanza per 
individuare e contrastare i bot. 

Ci sono vari siti web con più dettagli su questo metodo. 

**SITI WEB** - [Mailpoet: How to use honeypot traps](https://www.mailpoet.com/blog/email-honeypot-traps/), 
[Project Honeypot](https://www.projecthoneypot.org/), 
[Solution Factor: Honeypot Technique](https://solutionfactor.net/blog/2014/02/01/honeypot-technique-fast-easy-spam-prevention/), 
[Kijana Woodard: To Catch A Bot](https://kijanawoodard.com/to-catch-a-bot-use-a-honeypot)

## Captcha non di Google

Google non ha inventato il captcha, e ce ne sono altri disponibili che sono più attenti alla 
privacy. 

Quelli elencati qui sono tutti [liberi](open-source) e possono essere self-hosted. 

**SITI WEB** - [Captcheck](https://captcheck.netsyms.com/), 
[Click Captcha](https://github.com/Lokno/click-captcha), 
[Securimage](https://www.phpcaptcha.org/), 
[Django Simple Captcha](https://django-simple-captcha.readthedocs.io/en/latest/)

[torna alla pagina iniziale](index)
