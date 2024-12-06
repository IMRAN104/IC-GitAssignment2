# IC-GitAssignment2
  494  git init
  495  echo "# IC-GitAssignment2" >> README.md
  496  git add README.md
  497  git commit -m "first commit"
  498  git branch -M main
  499  git remote add origin https://github.com/IMRAN104/IC-GitAssignment2.git
  500  git push -u origin main
  501  git checkout -b feature-1
  502  git log
  503  git log
  504  echo "# Feature 1 Implementation

This is the first feature implementation.
" > feature1.txt
  505  git status
  506  git add .
  507  git commit -m "Add feature-1: Initial feature implementation"
  508  git push -u origin feature-1
  509  git push -u origin feature-1
  510  git log
  511  git checkout main
  512  git log
  513  git checkout -b feature-2
  514  echo "# Feature 2 Implementation

This is the second feature implementation.
" > feature2.txt
  515  git add .
  516  git commit -m "Add feature-2: Second feature implementation"
  517  git push -u origin feature-2
  518  git log
  519  git checkout main
  520  git log
  521  git checkout feature-1
  522  code .
  523  git status
  524  git add .
  525  git commit -m "Modified ReadMe"
  526  git push origin feature-1
  527  git push origin feature-1
  528  git log
  529  git rebase main
  530  git log
  531  git push origin feature-1
  532  git push origin feature-1
  533  git push origin feature-1
  534  git push origin feature-1
  535  git checkout feature-2
  536  git rebase main
  537  git push -f origin feature-2
  538  git checkout main
  539  git log
  540  git checkout feature-1
  541  git log
  542  git checkout main
  543  git branch --all
  544  git log
  545  git checkout feature-1
  546  git log
  547  git rebase main
  548  git log
  549  git checkout feature-2
  550  git rebase main
  551  git log
  552  git checkout main
  553  git push origin main
  554  git push origin main
  555  git push origin main
  556  git checkout feature-2
  557  git push origin feature-2
  558  git push origin feature-1
  559  git checkout feature-1
  560  git push origin feature-1
  561  git checkout main
  562  git pull origin
  563  git log
  564  git pull origin
  565  git log
  566  git branch -d feature-1
  567  git branch -d feature-2
  568  git push origin --delete feature-1
  569  git push origin --delete feature-2
  570  git log
  571  history
