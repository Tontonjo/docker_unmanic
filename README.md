# docker_unmanic

## Tonton Jo - 2021  
### Join the community:
[![Youtube channel](https://github-readme-youtube-stats.herokuapp.com/subscribers/index.php?id=UCnED3K6K5FDUp-x_8rwpsZw&key=AIzaSyA3ivqywNPQz0xFZBHfPDKzh1jFH5qGD_g)](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)
[![Discord Tonton Jo](https://badgen.net/discord/members/2NQskxZjfp?label=Discord%20Tonton%20Jo,%20&icon=discord)](https://discord.gg/2NQskxZjfp)
### Support the channel with one of the following link:
[![Buymeacoffee](https://badgen.net/badge/Buy%20me%20a%20Coffee/Link?icon=buymeacoffee)](https://www.buymeacoffee.com/tontonjo)
[![Infomaniak](https://badgen.net/badge/Infomaniak/Affiliated%20link?icon=K)](https://www.infomaniak.com/goto/fr/home?utm_term=6151f412daf35)
[![Express VPN](https://badgen.net/badge/Express%20VPN/Affiliated%20link?icon=K)](https://www.xvinlink.com/?a_fid=TontonJo)  
## Sources: 
[Unmanic Website](https://github.com/Unmanic/unmanic)  

## Alternative: 
[Handbrake](https://www.youtube.com/watch?v=dkpm3dGTi-I)  

## Docker command:  
```shell
docker run -d \
    --restart=unless-stopped \
    --name=unmanic \
    -e PUID=${PUID} \
    -e PGID=${PGID} \
    -e TZ=Europe/Zurich \
    -p 8888:8888 \
    -v /path/to/unmanic/config:/config \
    -v /path/to/unmanic/library:/library \
    -v /path/to/unmanic/temp:/tmp/unmanic \
    josh5/unmanic:latest
```
