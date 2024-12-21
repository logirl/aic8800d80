# aic8800d80

## How to use


```shell
git clone https://github.com/logirl/aic8800d80.git
cd aic8800d80
sudo cp -r fw/aic8800D80 /lib/firmware/
cd drivers/aic8800
make
sudo make install
sudo depmod
sudo modprobe aic8800_fdrv
sudo modprobe aic_load_fw
```
