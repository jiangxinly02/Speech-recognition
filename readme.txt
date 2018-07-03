三十四、语音识别
1.读取和绘制时间域音频数据
波形文件：.wav，时间-强度
代码：signal.py
2.基于傅立叶变换的频率域音频数据
代码：freq.py
y=Asin(ωx+φ)
A:振幅，能量
ω:角频率
2π/ω:时间频率
φ:相位
3.基于傅立叶变换的频率域滤波
代码：make.py
x           2**15
----- = -----
sigs      sigs.max
1.23456
123456
4.音频合成
代码：syn.py
5.音频特征值——MFCC，Mel Frequency Cepstrum Coefficient，梅尔频率倒谱系数
时间域 -FFT-> 频率域 -> MFCC
apple.wav
MFCCs -> 'apple'
代码：feature.py