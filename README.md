# ERC20_tutorial
ERC20 Tutorial


# Docker 실행 방법 <br>
# 열어주는 포트  9545, 8545, 7545, 3000, 3001  <br>
> docker run -it -p 9545:9545 -p 8545:8545 -p 7545:7545 -p 3000:3000 -p 3001:3001 --volume=$(pwd):/basic/  --name basic -d node 
# 포트 3009   //    에어드랍용
> docker run -it -p 3009:3009 --volume=$(pwd):/airdrop/ --name airdrop  --link king -d node