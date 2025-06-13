 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ls
TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ls -l
total 0
drwxr-xr-x  19 rochdidardor  staff  608 13 jui 22:47 TP Arboretum
drwxr-xr-x@  9 rochdidardor  staff  288 13 jui 22:03 TP Yoko_s Kitchen
drwxr-xr-x@  8 rochdidardor  staff  256 13 jui 22:35 tp-jean-doe-backup
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  clear
  UW PICO 5.09                                                                                         New Buffer
















































                                                                                                [ New file ]
^G Get Help                       ^O WriteOut                       ^R Read File                      ^Y Prev Pg                        ^K Cut Text                       ^C Cur Pos
^X Exit                           ^J Justify                        ^W Where is                       ^V Next Pg                        ^U UnCut Text                     ^T To Spell
  UW PICO 5.09                                                                                         New Buffer
















































                                                                                             [ Read 29 lines ]
^G Get Help                       ^O WriteOut                       ^R Read File                      ^Y Prev Pg                        ^K Cut Text                       ^C Cur Pos
^X Exit                           ^J Justify                        ^W Where is                       ^V Next Pg                        ^U UnCut Text                     ^T To Spell
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ls -l
total 0
drwxr-xr-x  19 rochdidardor  staff  608 13 jui 22:47 TP Arboretum
drwxr-xr-x@  9 rochdidardor  staff  288 13 jui 22:03 TP Yoko_s Kitchen
drwxr-xr-x@  8 rochdidardor  staff  256 13 jui 22:35 tp-jean-doe-backup
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  mkdir TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ls
TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  cd TP-Lotus/ls
cd: no such file or directory: TP-Lotus/ls
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ls
TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ls
TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  cd TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus  ls
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus  git init
Initialized empty Git repository in /Users/rochdidardor/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus/.git/
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git add .
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git commit -m "Initial commit: Lotus Elise specs page"
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git remote add origin https://github.com/Drr31/lotus-elise-specs.git
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git branch -M main
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git push --set-upstream origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Drr31/lotus-elise-specs.git'
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  ls
css        images     index.html js
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git checkout -b main
Switched to a new branch 'main'
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git push --set-upstream origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Drr31/lotus-elise-specs.git'
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  nano README.md
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  nano README.md
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  cat README.md
# Lotus Elise Specs – Fiche Technique Responsive

Ce projet a été réalisé dans le cadre d’un TP d’intégration web. Il s'agit d’une **fiche technique interactive** dédiée à la voiture Lotus Elise, avec un design responsive et moderne basé sur Bootstrap 5.

## 🚗 Description

Le site présente les caractéristiques de la Lotus Elise sous forme d’une page technique riche en composants visuels et interactifs :

- **Carrousel HD** pour les images de la voiture
- **Tableau comparatif responsive** pour mettre en valeur les spécifications techniques
- **Système de filtrage en JavaScript** pour simplifier la navigation dans les données

## 🎯 Objectifs pédagogiques

- Utiliser Bootstrap 5 pour une mise en page rapide et responsive
- Intégrer des composants dynamiques (carousel, tableau)
- Renforcer l’interactivité avec un filtrage en JavaScript natif

## 🛠️ Technologies utilisées

- HTML5
- CSS3
- Bootstrap 5
- JavaScript (Vanilla)

## ✍️ Auteur

Rochdi Dardor – Étudiant en informatique / MMI

 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git add .
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main ✚  git commit -m "Last commit: Lotus Elise specs page finishing"
[main (root-commit) 33d48f3] Last commit: Lotus Elise specs page finishing
 16 files changed, 10206 insertions(+)
 create mode 100644 .DS_Store
 create mode 100644 README.md
 create mode 100644 css/bootstrap.css
 create mode 100644 css/open-iconic-bootstrap.css
 create mode 100644 css/style.css
 create mode 100644 images/.DS_Store
 create mode 100644 images/image1.jpg
 create mode 100644 images/image2.jpg
 create mode 100644 images/image3.jpg
 create mode 100644 images/image4.jpg
 create mode 100644 images/image5.jpg
 create mode 100644 images/image6.jpg
 create mode 100644 images/image7.jpg
 create mode 100644 index.html
 create mode 100644 js/bootstrap.bundle.min.js
 create mode 100644 js/jquery-3.3.1.min.js
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  git push --set-upstream origin main
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 8 threads
Compressing objects: 100% (20/20), done.
Writing objects: 100% (21/21), 2.53 MiB | 39.21 MiB/s, done.
Total 21 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Drr31/lotus-elise-specs.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  ls
css        images     index.html js         README.md
s
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  s
zsh: command not found: s
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  ls
css        images     index.html js         README.md
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  cd ??.
zsh: no matches found: ??.
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  ls
css        images     index.html js         README.md
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/TP-Lotus   main  cd ../
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ls
TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  mkdir le-lait-meuuh
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  git init
Initialized empty Git repository in /Users/rochdidardor/Documents/Applying Projects/MyResume-1.0.0/assets/src/.git/
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  git checkout -b main
Switched to a new branch 'main'
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  git add .
warning: adding embedded git repository: TP Arboretum
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint: 	git submodule add <url> TP Arboretum
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint: 	git rm --cached TP Arboretum
hint:
hint: See "git help submodule" for more information.
warning: adding embedded git repository: TP Yoko_s Kitchen
  UW PICO 5.09                                                                                         New Buffer
















































                                                                                                [ New file ]
^G Get Help                       ^O WriteOut                       ^R Read File                      ^Y Prev Pg                        ^K Cut Text                       ^C Cur Pos
^X Exit                           ^J Justify                        ^W Where is                       ^V Next Pg                        ^U UnCut Text                     ^T To Spell
warning: adding embedded git repository: TP-Lotus
warning: adding embedded git repository: tp-jean-doe-backup
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  git commit -m "Initial commit: SEO-first mini-site Le lait Meeuuh"
[main (root-commit) b740bb6] Initial commit: SEO-first mini-site Le lait Meeuuh
 28 files changed, 1179 insertions(+)
 create mode 100644 .DS_Store
 create mode 160000 TP Arboretum
 create mode 160000 TP Yoko_s Kitchen
 create mode 160000 TP-Lotus
 create mode 100644 le-lait-meuuh/.DS_Store
 create mode 100644 le-lait-meuuh/comptes-rendus.html
 create mode 100644 le-lait-meuuh/contact.html
 create mode 100644 le-lait-meuuh/images/.DS_Store
 create mode 100644 le-lait-meuuh/images/curious_cow.jpg
 create mode 100644 le-lait-meuuh/images/google.png
 create mode 100644 le-lait-meuuh/images/index.html
 create mode 100644 le-lait-meuuh/images/moy_lait1.jpg
 create mode 100644 le-lait-meuuh/images/moy_vache1.jpg
 create mode 100644 le-lait-meuuh/images/moy_vache2.jpg
 create mode 100644 le-lait-meuuh/images/titevache1.jpg
 create mode 100644 le-lait-meuuh/images/titevache2.jpg
 create mode 100644 le-lait-meuuh/images/titevache3.jpg
 create mode 100644 le-lait-meuuh/index.html
 create mode 100644 le-lait-meuuh/licence.txt
 create mode 100644 le-lait-meuuh/membres.html
 create mode 100644 le-lait-meuuh/philo.html
 create mode 100644 le-lait-meuuh/robots.txt
 create mode 100644 le-lait-meuuh/scripts/html5shiv.js
 create mode 100644 le-lait-meuuh/scripts/index.html
 create mode 100644 le-lait-meuuh/sitemap.xml
 create mode 100644 le-lait-meuuh/styles/index.html
 create mode 100644 le-lait-meuuh/styles/layout.css
 create mode 160000 tp-jean-doe-backup
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  git remote add origin https://github.com/Drr31/le-lait-meuuh.git
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  git push --set-upstream origin main
remote: Repository not found.
fatal: repository 'https://github.com/Drr31/le-lait-meuuh.git/' not found
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  git remote add origin https://github.com/Drr31/le-lait-meuuh.git
error: remote origin already exists.
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  git push --set-upstream origin main
Enumerating objects: 28, done.
Counting objects: 100% (28/28), done.
Delta compression using up to 8 threads
Compressing objects: 100% (27/27), done.
Writing objects: 100% (28/28), 626.69 KiB | 31.33 MiB/s, done.
Total 28 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), done.
To https://github.com/Drr31/le-lait-meuuh.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  nano README.md
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main  git add  .
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  git push --set-upstream origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  ls
le-lait-meuuh      README.md          TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  cd le-lait-meuuh
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh   main ✚  ls
comptes-rendus.html images              licence.txt         philo.html          scripts             styles
contact.html        index.html          membres.html        robots.txt          sitemap.xml
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh   main ✚  cd ??.
zsh: no matches found: ??.
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh   main ✚  cd ../
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  ls
le-lait-meuuh      README.md          TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  mv README.md le-lait-meuuh
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ±✚  ls
le-lait-meuuh      TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ±✚  le le-lait-meuuh
zsh: command not found: le
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ±✚  git add .
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  git push --set-upstream origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  ls
le-lait-meuuh      TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src   main ✚  cd le-lait-meuuh
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh   main ✚  ls
comptes-rendus.html images              licence.txt         philo.html          robots.txt          sitemap.xml
contact.html        index.html          membres.html        README.md           scripts             styles
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh   main ✚  rm -rf "TP Arboretum" "TP Yoko_s Kitchen" "TP-Lotus" "tp-jean-doe-backup" .DS_Store
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh   main ±✚  git add -A
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh   main ✚  git commit -m "Nettoyage du dépôt : suppression des TP non liés à ce projet"
[main bc16ccc] Nettoyage du dépôt : suppression des TP non liés à ce projet
 2 files changed, 33 insertions(+)
 delete mode 100644 le-lait-meuuh/.DS_Store
 create mode 100644 le-lait-meuuh/README.md
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  brew install git-filter-repo
  UW PICO 5.09                                                                                         New Buffer
















































                                                                                             [ Read 104 lines ]
^G Get Help                       ^O WriteOut                       ^R Read File                      ^Y Prev Pg                        ^K Cut Text                       ^C Cur Pos
^X Exit                           ^J Justify                        ^W Where is                       ^V Next Pg                        ^U UnCut Text                     ^T To Spell
zsh: command not found: brew
  UW PICO 5.09                                                                                         New Buffer
















































                                                                                             [ Read 104 lines ]
^G Get Help                       ^O WriteOut                       ^R Read File                      ^Y Prev Pg                        ^K Cut Text                       ^C Cur Pos
^X Exit                           ^J Justify                        ^W Where is                       ^V Next Pg                        ^U UnCut Text                     ^T To Spell
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  brew --version
zsh: command not found: brew
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  which version
version not found
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  which brew
brew not found
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  cd /opt
 /opt  ls
homebrew R
 /opt  cd homebrew
 /opt/homebrew   stable  ls
bin              Cellar           completions      Dockerfile       etc              include          Library          manpages         package          requirements.txt share
Caskroom         CHANGELOG.md     CONTRIBUTING.md  docs             Frameworks       lib              LICENSE.txt      opt              README.md        sbin             var
 /opt/homebrew   stable  cd ../
 /opt  cd ../
 /  ls
Applications cores        etc          Library      private      System       Users        var
bin          dev          home         opt          sbin         tmp          usr          Volumes
 /  cd Users
 /Users  ls
Guest        rochdidardor Shared
 /Users  cd rochdidardor
 ~  ls
Applications                       Downloads                          Movies                             Postman                            SoapUI-Tutorials
Desktop                            Library                            Music                              Public
Documents                          material-design-colors.itermcolors Pictures                           Py-101
 ~  cd Desktop
 ~/Desktop  cd ../
 ~  ls
Applications                       Downloads                          Movies                             Postman                            SoapUI-Tutorials
Desktop                            Library                            Music                              Public
Documents                          material-design-colors.itermcolors Pictures                           Py-101
 ~  cd Documents
 ~/Documents  ls
Applying Projects Backup            Cours             Docs              IMGs              Projet_AOB@2024   STAGE_PAXILIA
 ~/Documents  cd Apl
cd: no such file or directory: Apl
 ✘  ~/Documents  cd Applying\ Projects
 ~/Documents/Applying Projects  ls
Canditature-ESGI Confedis         Keiken           monmaster2024    MyResume-1.0.0
 ~/Documents/Applying Projects  cd MyResume-1.0.0
 ~/Documents/Applying Projects/MyResume-1.0.0  ls
assets                 forms                  index.html             path                   portfolio-details.html Readme.txt             service-details.html   starter-page.html
 ~/Documents/Applying Projects/MyResume-1.0.0  cd assets
 ~/Documents/Applying Projects/MyResume-1.0.0/assets  ls
css    docs   img    js     scss   src    vendor
 ~/Documents/Applying Projects/MyResume-1.0.0/assets  cd src
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  ls
le-lait-meuuh      TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  nano ~/.zshrc
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  nano ~/.zshrc
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  source ~/.zshrc
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  brew --verison
Error: Unknown command: brew --verison
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  brew --version
Homebrew 4.5.2
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  brew install git-filter-repo
==> Auto-updating Homebrew...
Adjust how often this is run with HOMEBREW_AUTO_UPDATE_SECS or disable with
HOMEBREW_NO_AUTO_UPDATE. Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Downloading https://ghcr.io/v2/homebrew/portable-ruby/portable-ruby/blobs/sha256:fd162df7a06190ee800a9e6afd28f4466d33548821a480ba043cd927b44d60f7
##################################################################################################################################################################################################### 100.0%
==> Pouring portable-ruby-3.4.4.arm64_big_sur.bottle.tar.gz
==> Auto-updated Homebrew!
Updated 2 taps (homebrew/core and homebrew/cask).
==> New Formulae
abpoa                        chart-releaser               fastga                       kargo                        osx-trash                    rna-star                     tfmcp
addons-linter                clang-include-graph          fastk                        kraken2                      oterm                        ropebwt3                     timoni
alejandra                    claude-squad                 flip-link                    ktop                         oxen                         s6-rc                        tldx
autocycler                   concurrentqueue              flye                         ldcli                        pangene                      samply                       toml-bombadil
aws-lc                       cornelis                     foxglove-cli                 libbsc                       pdtm                         shamrock                     trimal
benchi                       cram                         gcc@14                       libpq@16                     perbase                      skalibs                      tsnet-serve
bento                        crd2pulumi                   gcli                         lima-additional-guestagents  polaris                      skani                        tun2proxy
blueprint-compiler           credo                        gerust                       lzsa                         polypolish                   sprocket                     urx
boa                          desed                        goshs                        mender-cli                   pulumictl                    sqruff                       webdav
bower-mail                   dvisvgm                      guichan                      miniprot                     qnm                          stringtie                    xml2rfc
breseq                       elf2uf2-rs                   htmlhint                     mongo-c-driver@1             rasusa                       style-dictionary             zsh-history-enquirer
bsc                          erlang@27                    hyper-mcp                    nova                         readsb                       sylph
btcli                        execline                     jwt-hack                     nx                           reckoner                     tabixpp
==> New Casks
5ire                                     firezone                                 font-leland                              moves                                    teleport@16
agentkube                                font-annotation-mono                     font-lxgw-marker-gothic                  mozilla-vpn                              textgrabber2
alifix                                   font-bitcount-grid-double                font-manufacturing-consent               nextcloud-talk                           timescribe
alisma                                   font-bitcount-grid-single                font-matangi                             onlook                                   tiny-shield
appexindexer                             font-bitcount-prop-double                font-menbere                             opensuperwhisper                         tourbox-console
azookey                                  font-bitcount-prop-single                font-savate                              pale-moon                                versatility
bison-wallet                             font-bitcount-single                     font-simple-icons                        passepartout                             voicenotes
brilliant                                font-charis                              fruit-screensaver                        peninsula                                voiden
burp-suite-professional@early-adopter    font-formudpgothic                       gg                                       revisionist                              warsaw
burp-suite@early-adopter                 font-gentium                             jetdrive-toolbox                         simpledemviewer                          wrkspace
cmpxat                                   font-gentium-book                        langflow                                 slideshower                              zen-privacy
container                                font-juisee                              little-snitch@nightly                    sparsity                                 zoho-cliq
eufymake-studio                          font-juisee-nf                           lobehub                                  tartelet                                 zoo-design-studio

You have 52 outdated formulae installed.

==> Downloading https://ghcr.io/v2/homebrew/core/git-filter-repo/manifests/2.47.0
##################################################################################################################################################################################################### 100.0%
==> Fetching git-filter-repo
==> Downloading https://ghcr.io/v2/homebrew/core/git-filter-repo/blobs/sha256:719c848f3c0611b909c5d2c3a603bbe5b29e8cbee1aacf7f31e92e4618b4aff0
##################################################################################################################################################################################################### 100.0%
==> Pouring git-filter-repo--2.47.0.all.bottle.tar.gz
🍺  /opt/homebrew/Cellar/git-filter-repo/2.47.0: 9 files, 362.8KB
==> Running `brew cleanup git-filter-repo`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  ls
le-lait-meuuh      TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  git filter-repo --subdirectory-filter le-lait-meuuh
Aborting: Refusing to destructively overwrite repo history since
this does not look like a fresh clone.
  (expected at most one entry in the reflog for HEAD)
Please operate on a fresh clone instead.  If you want to proceed
anyway, use --force.
 ✘  ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  ls
le-lait-meuuh      TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  cd le-lait-meuuh
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  ls
comptes-rendus.html images              licence.txt         philo.html          robots.txt          sitemap.xml
contact.html        index.html          membres.html        README.md           scripts             styles
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  ls
comptes-rendus.html images              licence.txt         philo.html          robots.txt          sitemap.xml
contact.html        index.html          membres.html        README.md           scripts             styles
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  ls
comptes-rendus.html images              licence.txt         philo.html          robots.txt          sitemap.xml
contact.html        index.html          membres.html        README.md           scripts             styles
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  ls
comptes-rendus.html images              licence.txt         philo.html          robots.txt          sitemap.xml
contact.html        index.html          membres.html        README.md           scripts             styles
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh  ↱ main  cd ../
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  ls
le-lait-meuuh      TP Arboretum       TP Yoko_s Kitchen  tp-jean-doe-backup TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  mkdir le-lait-meuuh-clean
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  cd le-lait-meuuh-clean
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh-clean  ↱ main  pwd
/Users/rochdidardor/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh-clean
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh-clean  ↱ main  cp -r "/Users/rochdidardor/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh"* .
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh-clean  ↱ main  ls
le-lait-meuuh       le-lait-meuuh-clean
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src/le-lait-meuuh-clean  ↱ main  cd ../
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  ls
le-lait-meuuh       le-lait-meuuh-clean TP Arboretum        TP Yoko_s Kitchen   tp-jean-doe-backup  TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  git init
Reinitialized existing Git repository in /Users/rochdidardor/Documents/Applying Projects/MyResume-1.0.0/assets/src/.git/
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  ls
le-lait-meuuh       le-lait-meuuh-clean TP Arboretum        TP Yoko_s Kitchen   tp-jean-doe-backup  TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main  ls
le-lait-meuuh-clean TP Arboretum        TP Yoko_s Kitchen   tp-jean-doe-backup  TP-Lotus
 ~/Documents/Applying Projects/MyResume-1.0.0/assets/src  ↱ main ±  cd le-lait-meuuh-clean
  UW PICO 5.09                                                                                         New Buffer
















































                                                                                             [ Read 33 lines ]
^G Get Help                       ^O WriteOut                       ^R Read File                      ^Y Prev Pg                        ^K Cut Text                       ^C Cur Pos
^X Exit                           ^J Justify                        ^W Where is                       ^V Next Pg                        ^U UnCut Text                     ^T To Spell
  UW PICO 5.09                                                                                  File: README.md                                                                                   Modified

# Le lait Meeuuh – Mini-site SEO-first & ultra-performant 🥛

Ce projet a été réalisé dans le cadre d’un TP portant sur l’optimisation SEO et la performance web. Il s’agit d’un **mini-site vitrine** pour une marque fictive de lait, pensé pour offrir une expérience $

## 📄 Description

Le site a été conçu selon une approche "SEO-first" et respecte les bonnes pratiques techniques du web :

- **HTML sémantique** pour une meilleure accessibilité et indexation
- Intégration de **Google Analytics (GA4)** via balises `gtag.js`
- Configuration d’un **robots.txt** pour autoriser l’indexation
- Inclusion d’un **sitemap.xml** compatible avec les moteurs de recherche
- Structure optimisée pour un **Core Web Vitals < 1 seconde**
- Fichiers légers, chargement rapide, responsive mobile-first

## 🎯 Objectifs pédagogiques

- Structurer un site vitrine avec un balisage HTML propre et sémantique
- Optimiser la performance et le temps de chargement
- Intégrer des outils d’analyse d’audience (GA + GTM)
- Respecter les critères Google Lighthouse / PageSpeed
- Mettre en place des fichiers SEO techniques (`robots.txt`, `sitemap.xml`)

## 🛠#️ Technologies utilisées

- HTML5
- CSS3
- Google Analytics (GA4)
- Google Tag Manager (optionnel)
- Sitemap / Robots.txt / Favicon

## 🌐 Déploiement

Ce projet peut être mis en ligne avec [GitHub Pages](https://pages.github.com/) ou tout autre hébergeur statique.

## ✍#️ Auteur

**Rochdi Dardor**
Étudiant en informatique / MMI# Le lait Meeuuh – Mini-site SEO-first & ultra-performant

Ce projet a été réalisé dans le cadre d’un TP axé sur l’optimisation SEO et les bonnes pratiques de performance web. Il s'agit d’un mini-site vitrine pour une marque fictive de lait, conçu pour charger e$

## 🥛 Description

Le mini-site a été conçu avec une attention particulière à la structure sémantique et à la performance avec google analytics integration (with robot.txt, sitemap.xml edits). Il intègre :

- Du **HTML sémantique** pour un meilleur référencement naturel

^G Get Help                       ^O WriteOut                       ^R Read File                      ^Y Prev Pg                        ^K Cut Text                       ^C Cur Pos
^X Exit                           ^J Justify                        ^W Where is                       ^V Next Pg                        ^U UnCut Text                     ^T To Spell
