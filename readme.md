TWORZENIE PLIKOW I FOLDEROW
============================

<h1> nalezy utworzyc katalog na pulpicie </h1>

sprawdzanie lokalizacji
-----------------------

  36  pwd

   38  cd Desktop
   39  dir
   40  ls -la
   41  cd..
   42  cd ..
   43  dir
   44  cd Music
   45  cd ..
   46  cd Music
>   47  ls -ls
>   48  md p
>   49  mdir p
   50  ls -la
   51  cls
   52  clear
   53  cd ..
   54  cd Desktop

### tworzenie katalogu 
   55  mkdir pierwsze repozytorium
   56  mkdir pierwsze_repozyt
   57  mkdir PG
   58  cd pg
   59  cd PG
   60  pwd
   61  mkdir r e k
   62  dir
   63  rm r e k
   64  rm -rd r e m
   65  rm -rd k
   66  ls
   67  git
   68  sudo apt-get install git
   69  git
   70  git --version

### tworzenie pliku

   71  touch test.txt
   72  nano test.txt
   73  ls -la
   74  git init
   75  ls -la
   76  git status
   77  git add test.txt
   78  git status
   79  git commit -m "zmiana"
   80  git config --global user.email "p.grodzicki81@gmail.com"
   81  git config --global user.name "wieliczkaPG"
   82  git status
   83  git log
   84  git commit -m "tworzenie pliku"
   85  git log
   86  nano test.txt
   87  git log
   88  git ststus
   89  git log
   90  nano test.txt
   91  git status
   92  git log
   93  nano test.txt
   94  git status
   95  git add .
   96  git commit -m "druga zmiana"
   97  git log
   98  nano test.txt
   99  git commit -m "trzecia zmiana"
  100  git add .
  101  git ststus
  102  git status
  103  git log
  104  git commit -m "trzecia zmiana"
  105  git add .
  106  git status
  107  git log
  108  git commit -m "trzecia zmiana"
  109  git remonte add orgini https://github.com/wieliczkaPG/PG.git
  110  git remote add orgini https://github.com/wieliczkaPG/PG.git
  111  git push -u origin master
  112  git remote add origin https://github.com/wieliczkaPG/PG.git
  113  git push -u origin master
  114  nano test.txt
  115  git status
  116  git add .
  117  git commit -m "czwarta zmiana"
  118  git log
  119  git push
  120  history . readme.md
  121  nano readme.md
  122  history > readme.md
[33mcommit 3130d8c95540610b47b8b4a655bbe76235e73647[m
Author: wieliczkaPG <p.grodzicki81@gmail.com>
Date:   Thu Oct 19 12:36:43 2017 +0200

    praca domowa

[33mcommit f2b0f99f45cb56526e0d257463a0561d10fb4817[m
Author: wieliczkaPG <p.grodzicki81@gmail.com>
Date:   Thu Oct 19 12:17:57 2017 +0200

    czwarta zmiana

[33mcommit 8a0a45e547bcec5fc156faee27d1afb46f9e5234[m
Author: wieliczkaPG <p.grodzicki81@gmail.com>
Date:   Thu Oct 19 11:33:42 2017 +0200

    trzecia zmiana

[33mcommit 398843b8b21415bf77e60802171bbe5d6da06ea5[m
Author: wieliczkaPG <p.grodzicki81@gmail.com>
Date:   Thu Oct 19 11:26:42 2017 +0200

    druga zmiana

[33mcommit 58e16b79f3bdc592e83ec5c4969d62172d027af2[m
Author: wieliczkaPG <p.grodzicki81@gmail.com>
Date:   Thu Oct 19 11:19:45 2017 +0200

    tworzenie pliku
