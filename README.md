# mosintV1


## O que é o MOSINT?

MOSINT é uma ferramenta OSINT para e-mails. Ele ajuda você a coletar informações sobre o e-mail de destino.

#### Características:

* Serviço de Verificação { Verifique se o e-mail existe }
* Verifique contas sociais com Socialscan
* Verifique violações de dados
* Encontre e-mails relacionados [API e PDFs]
* Encontre números de telefone relacionados
* Encontre domínios relacionados
* Digitalizar despejos Pastebin
* Pesquisa do Google
* Pesquisa de DNS


# key: chave de API necessária

\[não é necessário para executar o programa\]


| Service | Function | Status |
| :--- | :--- | :--- |
| [ipapi.co](https://ipapi.co/) - Public | More Information About Domain | :white\_check\_mark: |
| [hunter.io](https://hunter.io/) - Public | Related Emails | :white\_check\_mark: :key: |
| [scylla.so](https://scylla.so/) - Public | Database Leaks | :construction: |
| [breachdirectory.org](https://breachdirectory.org/) - Public | Password Leaks | :white\_check\_mark: :key: |
| [Intelligence X](https://intelx.io/)| Password Leaks | :white\_check\_mark: :key: |


## Serviços (APIs):

\[Já Vem com minhas Chave api\]

| Serviço | Função | Estado |
| :--- | :--- | :--- |
| [hunter.io](https://hunter.io/) - Público | API Key": "ff91e7e53d0ac705c99e755b398b80b9b17b75d5", | :white\_check\_mark: :key: |
| [breachdirectory.org](https://breachdirectory.org/) - Público | API Key": "be2b2ce0-7289-11ed-a5d1-99f90d862581", | :white\_check\_mark: :key: |
| [Inteligência X](https://intelx.io/)| API Key": "0ccf7d4d-28bc-4dde-83b5-b02801a631d2" | :white\_check\_mark: :key: |


Você pode desativar os recursos no `config.json` 

```javascript
[
{
  "verify-email.org API Key": "set API KEY here",
  "hunter.io API Key": "set API KEY here",
  "Breached Sites[leak-lookup.com API Key]": "set API KEY here",
  "Social Scan": "True",
  "Leaked DB": "True",
  "Related Phone Numbers" : "True",
  "Related Domains" : "True",
  "Pastebin Dumps": "True",
  "Google Search": "True",
  "DNS Lookup": "True"
}
]
```




#### Testado em:

- [x] Termux
- [x] Linux

# Como instalar - [x] Termux

***Necessario ter a linguem "golang"***

```
pip install -U pip

apt install golang
```

# Clonar o repositorio

```
git clone https://github.com/Gilmarsantosfilho/MosintV.1.0.git
cd mosintV1
```

```
pip3 install -r requirements.txt
```

```
python3 mosint.py -e gilmartikinho270@gmail.com
```


