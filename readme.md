# Backup [30-jan-2022]


### Before Adding Image files

> for i in *; do pngquant --quality=65-80 "$i" --ext _min.png ; done

> for i in *; do exiftool -all= $i ; done

### Random Key Generator

>for i in {1..2021}; do echo $RANDOM | md5sum | head -c 20 > $i.key; done


### Tools

- veracrypt
- storj
- duplicity
- aws
- bitwardan

### Backup key signature:

 - key: backups@88....*..
**21E1132C39BB6370AED8796B5FA41278C438C6EA**

------------


![alt text](LINK)
