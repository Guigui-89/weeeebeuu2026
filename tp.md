1.  $ mkdir tpLinux

2.  $ tree ou $ ls -l

3.  $ cd ./tpLinux
    $ touch {fic1,fic2,exoos}.txt
    $ touch {fichier,exos}.md
    $ touch image.jpg

4.  $ mkdir dosA
    $ mkdir dosD
    $ cd ./dosA
    $ mkdir dosB
    $ mkdir dosC
    $ cd ../
    $ tree
5.  $ mv ./fi* ./dosA/dosB

6.  $ cd ./dosA/dosB
    $ cp ./fic1.txt ../
    $ cp ./fic2.txt ../dosC
    $ cp ./fichier.md ../../dosD

7.  $ cd ../
    $ cd ../
    $ echo "Bonjour tout le monde" > fic1.txt
    $ ls -l fic1.txt

8.  $ ls ./*.???

9.  $ mv ./exoos.txt ./exos.txt

10. $ cd ../
    $ touch supprimer.sh
    $ echo -e "rm -r ./tpLinux" > ./supprimer.sh
    $ chmod u+x ./supprimer.sh
    $ ./supprimer.sh