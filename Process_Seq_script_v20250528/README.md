## shell 脚本
```
bash process_sequences_countv20250528.sh -p   "GATCAGTCGGACAAGCAACAGTTCCGACATGATC,AGATCGGAAGA"  -N 1000000000
```
## 分离计数和生成脚本
```
python3 Process_gen.py -p 序列 -N 1000000000 --write-matching-reads
这个文件夹下面的gz文件
```

```
python Split.py  --sep1  序列  -i fastq.R1.gz
```
