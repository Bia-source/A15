// quando NAO tiver um repositório criado
// para criar um repositório e salvar as primeiras atualizações
git init
git add .
git commit -m "mensagem"
git remote add origin https://GitHub/seu-username/nome-repositorio.git
git push origin nomeBranch

// quando JÁ tiver um repositório criado e conectado
// para salvar atualizações novas
git pull origin nomeBranch
git add .
git commit -m "mensagem"
git push origin nomeBranch
