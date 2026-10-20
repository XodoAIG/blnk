# GOLAND CONFIGURATION:

## ✅ PARTE 1 — Configuration SERVER:
```
1. Abra o menu de configurações

Run → Edit Configuration → Go Build

2. Configure os campos assim:

Name:                   blnk-server
Run kind:               Package
Package path:           github.com/blnkfinance/blnk/cmd
Working directory:      /home/rafael/xodo/blnk-petropix
Program arguments:      start
```

## ✅ PARTE 2 — Configuration WORKER:
```
1. Igual ao SERVER so muda:

Program arguments: workers
```

## ✅ PARTE 3 — Configuration Compound:

```
Run → Edit Configuration → Compound

Name: blnk-all

Selecione:
 - blnk-server
 - blnk-worker
```