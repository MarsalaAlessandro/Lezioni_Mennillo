# history dei comandi

   12  mkdir lab_linux
   13  cd lab_linux
   14  pwd
   15  mkdir progetti; documenti; backup;
   16  mkdir progetti; mkdir documenti; mkdir backup
   17  ls
   18  cd progetti
   19  mkdir app_a; mkdir app_b
   20  ls
   21  pwd
   22  tree
   23  sudo apt install tree
   24  tree
   25  cd ../
   26  tree
   27  cd lab_linux
   28  ls
   29  cd progetti
   30  cd app_a
   31  touch main.py
   32  cd ../app_b
   33  touch note.txt
   34  cd ../documenti
   35  cd ../../documenti
   36  touch report.doc
   37  ls
   38  cd ../
   39  cd progetti/app_a
   40  cd ../../
   41  cd documents
   42  ls
   43  cd documenti
   44  cd /home/lab_linux/
   45  cd progetti/app_b
   46  cd /home/utente/lab_linux/
   47  cd /home/
   48  ls
   49  cd ubunut
   50  cd ubuntu
   51  ls
   52  cd lab_linux/documenti
   53  cd /home/ubuntu/lab_linux/
   54  cd //home/ubuntu/lab_linux/
   55  cd  progetti/app_b
   56  cd ../../documenti
   57  cd -
   58  cp ../app_a/main.py ../../backup
   59  cd ../../backup
   60  ls
   61  cp ../documenti/report.doc ./report_backup.doc
   62  ls
   63  cp ../progetti/app_a ./
   64  cp ../progetti/app_a ./app_a_backup
   65  ls
   66  cp -r ../progetti/app_a ./app_a_backup
   67  ls
   68  mv ../progetti/app_b/note.txt ../progetti/app_b/appunti.txt
   69  cd ../progetti/app_b/note.txt
   70  cd ../progetti/app_b/
   71  ls
   72  mv ../../documenti/report.doc ../../backup/
   73  ls ../../backup/
   74  mv ./ ../app_beta
   75  cd ../
   76  mv ./app_b ./app_beta
   77  ls
   78  cd ../../
   79  mkdir progetto_web
   80  cd progetto_web
   81  mkdir frontend
   82  mkdir backend; mkdir docs; cd frontend; mkdir css
   83  ls
   84  touch index.html
   85  cd ./css; touch style.css
   86  cd ../../backend
   87  touch server.py
   88  cd ../docs; touch README.md
   89  cp ../backend/server.py ../../lab_linux/backup; mv ../../progetto_web ../../lab_linux/backup
   90  rm ../../lab_linux/backup/progetto_web
   91  cd ../../lab_linux/backup
   92  cd ../../lab_linux/
   93  cd ../../
   94  ls
   95  mv ./ ../backup_finale
   96  mv ../backup ../backup_finale
   97  ls
   98  history
