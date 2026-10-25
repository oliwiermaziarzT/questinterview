# D3D12 Hello Triangle

Przykładowa aplikacja Direct3D 12 (Hello Triangle).

## Wymagania (Windows)

- Windows 10/11
- [Visual Studio 2022](https://visualstudio.microsoft.com/) z workloadem **Desktop development with C++**
- Windows 10 SDK (instalowany razem z VS)
- Karta graficzna z obsługą DirectX 12

## Odpalanie

1. Sklonuj repozytorium i otwórz w Visual Studio plik:
   ```
   src/D3D12HelloTriangle.slnx
   ```
2. Przy pierwszym otwarciu przywróć pakiety NuGet (Direct3D Agility SDK + DXC):
   - PPM na rozwiązanie → **Restore NuGet Packages**
   - albo poczekaj, aż VS zrobi to automatycznie
3. Ustaw konfigurację **Debug | x64** (albo Release | x64).
4. Zbuduj i uruchom: **F5** (z debuggerem) albo **Ctrl+F5** (bez).

Exe ląduje w:

```
src/bin/x64/Debug/D3D12HelloTriangle.exe
```

(dla Release: `src/bin/x64/Release/`).

Możesz też odpalić exe bezpośrednio z tego folderu — shadery `.cso` są kopiowane obok niego przy buildzie.
