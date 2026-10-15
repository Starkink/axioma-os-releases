# Axioma OS — выпуски

Готовые установщики приложения онлайн-школы [Axioma](https://axiomaschool.com) для Windows и Linux. Исходного кода здесь нет, только выпуски.

**Скачать последнюю версию: [axiomaschool.com/app](https://axiomaschool.com/app)**

| Система | Файл |
| --- | --- |
| Windows 10 и 11 | `axioma-setup-<версия>.exe`: установка меньше минуты, без прав администратора |
| Windows, на флешку | `axioma-os-portable-<версия>.zip`: все данные лежат рядом с программой |
| Любой Linux | `axioma-os-<версия>.AppImage`: скачать, разрешить запуск, открыть |
| Ubuntu, Mint, Debian, Astra | `axioma-os-<версия>.deb` |
| Fedora, Альт, РЕД ОС | `axioma-os-<версия>.rpm` |

Приложение для Windows и AppImage обновляются сами. Обновления подписаны ключом школы, и неподписанное обновление приложение не примет.

## Проверить файл

В каждом выпуске лежит `SHA256SUMS.txt` с контрольными суммами. Сравнить сумму файла с ней:

```
# Linux
sha256sum -c SHA256SUMS.txt --ignore-missing

# Windows (PowerShell)
Get-FileHash .\axioma-setup-0.3.1.exe -Algorithm SHA256
```
