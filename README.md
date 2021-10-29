# docker_unmanic

## Tonton Jo - 2021

If you find this usefull, please consider supporting my work:  
- Join me on my [Youtube Channel](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)  
- <a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a> <a href="https://www.infomaniak.com/goto/fr/home?utm_term=6151f412daf35"><img src="https://i.ibb.co/KjWSd95/banner-bleu.png"></a> </a> <a href="https://www.xvinlink.com/?a_fid=TontonJo"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/79/ExpressVPN-logo.svg/261px-ExpressVPN-logo.svg.png"></a>  

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
