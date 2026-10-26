# DirectX Triangles

## Wymagania (Windows)

- Windows 10/11
- [Visual Studio 2022](https://visualstudio.microsoft.com/) z workloadem **Desktop development with C++**
- Windows 10 SDK

## Odpalanie

1. Sklonuj repozytorium lub pobierz folder i otwórz w Visual Studio plik:
   ```
   src/D3D12HelloTriangle.slnx
   ```
2. Przy pierwszym otwarciu przywróć pakiety NuGet
   - PPM na rozwiązanie → **Restore NuGet Packages**
3. Ustaw konfigurację **Debug  x64** 
4. Dodaj argument (liczba trojkatow)
   1. Kliknij prawym przyciskiem myszy na projekt w Solution Explorerze i wybierz **Properties**
   2. Przejdź do zakładki **Configuration Properties** -> **Debugging**.
   3. W polu **Command Arguments** wpisz pożądaną liczbę trójkątów
   4. Kliknij **Apply** / **OK**.
4. Zbuduj i uruchom
