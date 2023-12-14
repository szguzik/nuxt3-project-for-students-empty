# Nuxt 3 Instrukcja - klonowania projektu

Założenie  
System kontroli wersji jest zainstalowany

## GIT
Sprawdzenie czy GIT jest zainstalowany  
Otwórz terminal i wpisz polecenie

```bash
git --version
```
Jeżeli zostanie wyświetlona wersja to system kontroli wersji jest zainstalowany - przejdź od razu do sekcji Klonowanie

W przypadku wyświetlenia komunikatu o braku rozpoznanego polecenia należy wykonać poniższe kroki:  
1. Pobrać oprogramowanie ze strony [git](https://git-scm.com/)

2. Zainstalować - tutaj będzie konieczna pomoc działu IT w celu wprowadzenia hasła

3. W terminalu wykonać polecenia poniżej analogiczne uzupełnione o Twoje dane 

```bash
git config --global user.name "Jan Kowalski"  
git config --global user.email "youremail@domain.com"  
```
4. Ponownie sprawdź wersję GIT-a poleceniem
```bash
git --version
```
5. Wykonaj poniższe polecenia

## Klonowanie
```bash
git clone https://github.com/szguzik/nuxt3-project-for-students-empty.git
```

## Otwieranie katalogu projektu w terminalu
```bash
cd nuxt3-project-for-students-empty
```
## Instalacja

```bash
npm install
```

## Uruchamianie:

```bash
npm run dev
```
