Reviaco Bootanimation
=========
The Official Reviaco Bootanimation.

![initial version screenshot](https://github.com/ozonos/ozon-plymouth/blob/master/preview.png)

### See it in action!
**YouTube** video is available [here](http://www.youtube.com/watch?v=RfNinSwSrjE).

### Installation

- **Move** 'reviaco-bootanimation' to `/lib/plymouth/themes`.

- Open a terminal and **paste**:
```
sudo update-alternatives --install /lib/plymouth/themes/default.plymouth default.plymouth /lib/plymouth/themes/reviaco-bootanimation/reviaco-bootanimation.plymouth 100
```

- Then **run**:
 
`sudo update-alternatives --config default.plymouth`

And **select Reviaco**.

- Finally **paste**:

`sudo update-initramfs -u`

### License

This project is licensed with GPL version 3 and later. See LICENSE for more details.
