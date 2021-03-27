# bash-script-activate-conda
bash script activate conda


Bình thường khi dùng bash auto các thao tác trên ubuntu, và một trong những thao tác đó là cần activate môi trường anaconda lên (Để dùng python), nhưng nếu bạn chỉ activate một cách bình thường  là conda activate env_name thì không có được, bạn cần phải activate trong bash giống như câu lệnh bên dưới
```
source ~/anaconda3/etc/profile.d/conda.sh
conda activate auto2
python index.py
```

sau đó auto bình thường, có thể dùng pm2 để quản lý file python chạy ngầm
