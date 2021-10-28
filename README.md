# docker_unmanic

## Tonton Jo - 2021
Join me on Youtube: https://www.youtube.com/c/tontonjo

If you find this usefull, please think about
<a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a>
and to [Subscribe to my youtube channel](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)

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
