# Caesarova šifra (část 1/2)

## Namespace
```
cipher
```
## Popis
Rozšíření poskytuje čtyři metody pro zašifrování a dešifrování textu/znaku pomocí Caesarovy šifry s libovolným posunem. Z důvodu jednoduššího překladu rozšíření pracuje pouze s anglickou abecedou, je ale schopno přeložit diakritiku na znak bez diakritiky.

 
## Metody
### Zašifruj text %text caesarovou šifrou s posunem %key
- Zašiftuje zadaný text caesarovou šifrou s libovolným posunem
- Parametry:
    - text k zašifrování (text)
    - klíč (posun) - může být kladný i záporný (číslo)
- Návratová hodnota: zašifrovaný text (text)

### Dešifruj text %text caesarovou šifrou s posunem %key
- Dešiftuje zadaný text caesarovou šifrou s libovolným posunem
- Parametry:
    - text k dešifrování (text)
    - klíč (posun) - může být kladný i záporný (číslo)
- Návratová hodnota: dešifrovaný text (text)

### Zašifruj znak %character caesarovou šifrou s posunem %key
- Zašiftuje zadaný znak caesarovou šifrou s libovolným posunem
- Parametry:
    - text k zašifrování (text)
    - klíč (posun) - může být kladný i záporný (číslo)
- Návratová hodnota: zašifrovaný text (text)
#### Dešifruj znak %character caesarovou šifrou s posunem %key
- Dešiftuje zadaný znak caesarovou šifrou s libovolným posunem
- Parametry:
    - text k dešifrování (text)
    - klíč (posun) - může být kladný i záporný (číslo)
- Návratová hodnota: dešifrovaný text (text)
