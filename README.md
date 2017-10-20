# CelluCon.PID

### スマフォ（Java）PID制御、遠隔PIDパラメータチューニング
* スマフォの加速度センサを用いてBluetoothにつながっているサーボモーターをPID制御する。まずは倒立2輪車に挑戦中。
* スマフォセンサ情報はWeb画面のPCで取り込んで解析し、最適なPIDパラメーターを計算する仕組み。
* Web画面で解析したPIDパラメーターをスマフォのPID計算式に遠隔代入してパラメーターの最適値をリアルタイムで検証する。
* PIDのオートチューニングをやりやすくする仕組み。
