## Commands

Docker network create -d bridge localnet

Docker run -d --network localnet --name webApp -p 80:8080 webapp

Docker run -it --network localnet --name netwoorkLocal alpine sh

ping webApp